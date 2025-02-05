# Cursor 使用指南及 Cursor Pro 会员订阅详解

## 1. 背景

### AI IDE 选择

1. **Bolt.new**：快速构建全栈原型的浏览器 IDE，适合轻量化开发需求。
2. **Lovable.dev**：用户友好型 IDE，专注于非技术用户和小团队的快速协作开发。
3. **Windsurf**：企业级 IDE，提供深度上下文理解和跨 IDE 兼容性，适合团队合作。
4. **Cursor AI**：全能型，多模型支持的高级 IDE，适合需要实时错误检测的开发者。
5. **Aide**：开源多语言 IDE，适合教育用途和新手学习复杂代码。
6. **V0 by Vercel**：前端专用 IDE，直观易用，适合快速生成 React 和 Next.js 项目。
7. **Replit Agent**：集成数据库和快速部署能力，适合数据密集型项目的开发。
8. **Devin AI**：高端自治 IDE，支持复杂工程项目，适合寻求尖端技术的团队。
9. **Github Copilot inside VSCode**：GitHub Copilot 免费计划提供每月 2000 次代码补全和 50 次聊天请求，支持 GPT-4o 和 Claude 3.5 Sonnet 模型。

### AI 辅助编程模型选择

- **OpenAI o1**：架构设计师、算法高手
- **Cursor/Claude 3.5 Sonnet**：码农
- **v0/Claude 3.5 Sonnet**：网页设计制作
- **Gemini**：反编译、反向工程师

## 2. Cursor 使用

![Cursor 界面](https://bbtdd.com/img/9187543076863.webp)

Cursor 是由 Anysphere 实验室打造的代码编辑器，基于 VSCode 修改派生，因此所有在 VSCode 上的配置都能够导入到 Cursor 里使用。如果你平常使用 VSCode 进行开发，那么你可以非常便捷地迁移过来。

### 主要功能

Cursor 是一款集成人工智能（AI）功能的代码编辑器，旨在提升开发者的编程效率和代码质量。作为 Visual Studio Code 的分支，Cursor 保留了其熟悉的界面和扩展支持，同时引入了强大的 AI 功能。该编辑器于 2023 年 1 月正式发布，由 Aman Sanger 和 Michael Shuffett 创立。2024 年 8 月，Cursor 宣布获得 A 轮 6000 万美元融资，估值达到 4 亿美元。在开发者社区中，Cursor 获得了积极的反馈，用户赞赏其在代码补全、错误检测和代码重构等方面的出色表现，以及友好的界面设计。

**主要功能：**

- **智能代码补全**：Cursor 利用 AI 模型，根据上下文提供代码补全建议，帮助开发者快速编写代码。
- **自然语言编程**：开发者可以使用自然语言描述所需的功能，Cursor 将其转换为相应的代码，实现更直观的编程体验。
- **代码库理解**：Cursor 能够分析整个代码库，提供全局搜索、代码导航等功能，方便开发者理解和维护大型项目。
- **多模型支持**：Cursor 支持多种 AI 模型，如 OpenAI 的 GPT-4、Claude 3.5 和 Meta 的 Llama 3.1，开发者可根据需求选择合适的模型。
- **大陆直连**：可以在大陆直连这些模型。（优势极大）

### 基本设置

主要参考 VSCode，个人有一些使用习惯：

- **打开文件窗口不覆盖**：`Enable Preview`，去掉这个选项的勾。
- **修改 Cursor 的导航栏位置**：从横向改为纵向，在设置中搜索：`workbench.activityBar.orientation`，修改为 `vertical` 即可。
- **关闭自动更新**：参考 [Cursor 如何安装旧版本，Cursor 怎么禁止自动更新教程](https://blog.csdn.net/AIPioneerShark/article/details/144562738)。

### 基本使用

👉 [WildCard | 一分钟注册，轻松订阅海外线上服务](https://bbtdd.com/WildCard)

### `.cursorrules` 技巧

本节摘选自 [Steven W. 对 Cursor 中 .cursorrules 的技巧总结↓-黄建同学微博](https://weibo.cn/sinaurl?u=https%3A%2F%2Fweibo.com%2F5648162302%2FP6kwS1sUW)；更多内容可参考[【集合】AI 编程工具 Cursor-黄建同学微博](https://weibo.com/ttarticle/p/show?id=2309405099227071250763)。

> `.cursorrules` 是一个存放在项目根目录的特殊文件，用于自定义本项目内 Cursor 中的 AI 辅助规则。使用步骤：
> 1）创建文件：在项目根目录创建 .cursorrules 文件。
> 2）定义规则：按照上文的建议，定义项目背景、编码标准和文件结构等规则。
> 3）重启 Cursor：在 Cursor 中，重启 AI 助手以加载新的 .cursorrules 文件。
> 4）实时调整：当项目需求发生变化时，及时更新 .cursorrules 文件。

**全局的 AI 配置提示词**：`File -> Preferences -> Cursor Settings -> Rules for AI`
![AI 配置](https://bbtdd.com/img/9199104379.webp)

### Cursor Pro 与 Hobby 的区别

![Cursor Pro 与 Hobby 区别](https://bbtdd.com/img/758739774806.webp)

截止到 2024 年 12 月 26 日，提供免费版（Hobby）和专业版（Pro）两种订阅选项。以下是两者的主要区别：

**免费版（Hobby）：**

- 试用期：新用户可免费试用 Pro 版功能 14 天。
- 使用限制：每月 2000 次代码生成。
- 每月 50 次使用慢速高级模型（如 GPT-4、GPT-4o、Claude 3.5 Sonnet）。
- 无限次使用 cursor-small 模型。（效果很差）

**专业版（Pro）：**

- 无限制：无限次代码生成。
- 高级模型使用：每月 500 次快速使用高级模型（如 GPT-4、GPT-4o、Claude 3.5 Sonnet）。
- 无限次慢速使用高级模型。
- 额外功能：每日 10 次使用 o1-mini 模型。

### Cursor 订阅

- **方法一**：由于新用户都有免费 14 天的试用机会，可以换不同邮箱进行白嫖，但是白嫖过多会检测到同一设备。网上有大量修改机器码的白嫖教程。
- **方法二**：[cursor-vip](https://github.com/kingparks/cursor-vip/blob/main/README_CN.md)：每 8 个设备共享一个 Pro 账号。通过推广 cursor-vip，用户可以获得免费使用时间，对方也可享受免费试用。
- **方法三**：网上充斥着大量某虚拟卡（Wildc*rd）的推广（病毒营销），需要交纳手续费，不建议使用。开的卡是有效期 2 年的虚拟**卡，开卡费包含两年年费，算下来 100 元 RMB。推广者会得到奖励。
- **方法四**：直接订阅（虚拟卡就莫名其妙）。
  ![订阅界面](https://bbtdd.com/img/410223317479797.webp)
  实测发现，官方直接就支持中国银联（UnionPay），因此，只需要带中国银联标识的普通信用卡（国内的信用卡都带中国银联标识）即可直接订购，无需节外生枝。
  ![订阅成功](https://bbtdd.com/img/134670983518376.webp)
  没有额度的学生信用卡一样可以订阅成功。可以直连以及支持中国银联显示出官方对大陆市场的重视。订阅后界面如下：
  ![订阅后界面](https://bbtdd.com/img/60114070954510.webp)