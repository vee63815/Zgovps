# Cursor：智能 AI 代码生成工具，你还没用过？

## 概述

**Cursor.so** 是一款集成了 **GPT-4** 的强大代码生成工具，国内用户可以直接访问。它能够帮助你快速编写、编辑和讨论代码，支持多种编程语言，如 Python、Java、C#、JavaScript 等。无论是代码生成、重构、理解还是优化，Cursor.so 都能大幅提升开发效率。

强烈推荐程序员们安装使用，它将为你的编码工作带来革命性的效率提升。本文将详细介绍 Cursor 的安装和使用方法。

## 安装

### 2.1 安装 Cursor

访问官网：[www.cursor.so/](https://www.cursor.so/)

支持的操作系统包括 **Mac**、**Windows** 和 **Linux**，根据你的电脑系统进行下载。

![image.png](https://p9-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/f0801693768b40b9a99bdbafccf399bd~tplv-k3u1fbpfcp-zoom-in-crop-mark:1512:0:0:0.awebp)

### 界面介绍

Cursor 是一款独立的应用，界面风格类似 **VS Code**，但功能上稍显简化。界面主要包含三个菜单栏：**File**、**Edit**、**View**，以及右上角的四个图标。重点关注 **View 菜单下的 Command Palette** 和右上角的设置图标。

![image.png](https://p9-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/107e029d9b5c4c48ac8d062eeafc71a7~tplv-k3u1fbpfcp-zoom-in-crop-mark:1512:0:0:0.awebp)

打开 **Command Palette** 后，可以看到六个选项，其中最重要的四个是：

- **Ctrl+K**：负责代码生成与编辑
- **Ctrl+L**：负责代码理解和注释

![image.png](https://p1-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/3f67d83edf42477ca9a7709fb1b22ee5~tplv-k3u1fbpfcp-zoom-in-crop-mark:1512:0:0:0.awebp)

点击 **Setting** 按钮，进入设置界面。Cursor 编辑器支持 **vim** 和 **emacs** 模式，还可以绑定 **Copilot** 并安装不同语言的 server。

![image.png](https://p3-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/01df312e910c40cd91af62f18fc39813~tplv-k3u1fbpfcp-zoom-in-crop-mark:1512:0:0:0.awebp)

## 使用

![image.png](https://p1-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/687aa8554f4b4601bfef3323af4bf622~tplv-k3u1fbpfcp-zoom-in-crop-mark:1512:0:0:0.awebp)

### 3.1 生成代码

首先，创建一个 **Java** 文件，然后使用 **Ctrl + K** 输入你希望生成的代码内容。

![image.png](https://p6-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/054a0076b4f345ba89aa93c2c5b3dcf7~tplv-k3u1fbpfcp-zoom-in-crop-mark:1512:0:0:0.awebp)

生成的代码如下：

![image.png](https://p9-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/e432e04dc83d4724bb71e6dd20c8f420~tplv-k3u1fbpfcp-zoom-in-crop-mark:1512:0:0:0.awebp)

**注意**：如果代码生成到一半终止，可以重新呼出对话框，输入“继续”即可。

### 3.2 与代码“对话”

你可以选择生成的代码部分，提出问题或要求优化。有两个选项：

- **Edit**：告诉它你的诉求，让它帮你修改代码。
- **Chat**：提出问题，让它为你解答。

![image.png](https://p6-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/4addc11e55974588bf53c110ea176081~tplv-k3u1fbpfcp-zoom-in-crop-mark:1512:0:0:0.awebp)

#### 3.2.1 对话

![image.png](https://p6-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/fa51ec98b9724a9cb46af57b35b40fa1~tplv-k3u1fbpfcp-zoom-in-crop-mark:1512:0:0:0.awebp)

**提示**：你不仅可以与生成的代码“对话”，还可以将 **JDK**、开源项目或自己的业务代码粘贴到这里，让它帮你理解、优化或寻找潜在的 BUG。

![image.png](https://p9-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/41249f0f20814efa81f12ea45ab584cd~tplv-k3u1fbpfcp-zoom-in-crop-mark:1512:0:0:0.awebp)

#### 3.2.2 修改

它会根据你的意思进行修改。如果你认为符合要求，点击 **Accept** 生效，否则点击 **Reject** 拒绝修改。

![image.png](https://p1-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/d79f20d734714da08a1d69940b36ee00~tplv-k3u1fbpfcp-zoom-in-crop-mark:1512:0:0:0.awebp)

点击 **Accept** 后，修改成功：

![image.png](https://p9-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/0e49bffe86c14aaaaa8bf30a3d4f08c1~tplv-k3u1fbpfcp-zoom-in-crop-mark:1512:0:0:0.awebp)

虽然修改不一定是最优的，但基本符合需求。

## 总结

本文简要介绍了如何安装和使用 **Cursor**。通过它，你可以生成基础代码，大幅提升工作效率。未来，人工智能必将为开发工具带来更大变革。

**注意**：虽然 Cursor 可以通过自然语言生成代码，但目前仍不完美。如果生成的代码不符合要求，可以通过优化表达、重新生成或对话调整来逐步完善。此外，务必注意数据安全，避免泄露敏感信息。所有修改建议仅供参考，需自行甄别。

👉 [WildCard | 一分钟注册，轻松订阅海外线上服务](https://bbtdd.com/WildCard)