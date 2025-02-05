# 开发者新选择：利用 DeepSeek 实现智能编程的免费方案

## 前言

去年下半年，Cursor 的火爆让许多不懂代码的小白也能轻松搭建网站和应用，推动了独立开发的潮流。然而，每月20美元的价格并不亲民。此时，可以尝试使用 Cline、Aider Composer + Continue 等插件，搭配其他大模型后端，实现类似的效果。

## AI编程的两种模式

AI编程目前主要有两种模式：

1. **全自动模式**（如 Cline、Aider 等工具）：你提供需求，AI生成代码，适合小型项目，如单页网页或命令行工具。不过，复杂项目仍需谨慎。
2. **半自动模式**（如 Copilot）：你与AI协作编写代码，AI提供补全和查漏补缺，类似于副驾驶的角色。

**重要提示**：除非完全依赖AI，否则生成的代码切勿直接使用。建议使用Git等版本控制工具，多次提交，便于对比和发现问题。

## Cline的问题

Cline 的一个问题是 token 消耗过快。测试发现，还未完成一个页面，就已消耗了20元的 token。

## 使用本地部署的 DeepSeek 模型

由于 Cline 的自动写代码费用高昂，转而尝试本地部署 DeepSeek 模型。DeepSeek 的蒸馏模型效果不错，可作为 Cline 的后端。

### 遇到的问题

默认配置下，Cline 无法正常工作，提示模型能力不足。原因是 Cline 需要模型具备较强的代理式推理、分步骤思考和复杂指令执行能力。

### 调整上下文长度

上下文长度指模型一次推理能处理的 Token 数量上限。如果容量不足，多轮指令或大段文本会被截断或遗忘。

### 在 Ollama 中创建大上下文长度的模型镜像

通过创建 `deepseek-r1-14b-32k.ollama` 文件，并设置上下文长度为32K，可以解决上下文不足的问题。

bash
ollama create deepseek-r1-14b-32k -f deepseek-r1-14b-32k.ollama


完成后，Cline 中切换至该模型即可使用32K的上下文容量。

## 映射 Ollama 服务到本地

将模型部署在服务器上，通过SSH隧道转发至本地：

bash
ssh -L 11434:localhost:11434 用户名@服务器地址 -p 端口


## 配置 Cline 插件

在 Cline 插件中选择 Ollama 作为 API Provider，并选择创建的 deepseek-r1-14b-32k 模型。

![image](https://bbtdd.com/img/675403150211585.webp)

## 实现效果

测试生成“新年祝福生成器”代码，发现 DeepSeek-14B 的代码能力有限，部分代码需手动修复。直接与模型对话生成的代码则能直接运行。

![image](https://bbtdd.com/img/770710508941204.webp)

## 部署 LocalAI（可选）

LocalAI 可作为兼容 OpenAI API 的网关，加载本地模型进行推理。由于 Cline 插件支持直接调用 Ollama，此次未部署 LocalAI。

👉 [WildCard | 一分钟注册，轻松订阅海外线上服务](https://bbtdd.com/WildCard)

## 参考资料

## 小结

DeepSeek 模型勉强可用，但 Cline 的 token 消耗较大，未来尝试其他插件以改善体验。