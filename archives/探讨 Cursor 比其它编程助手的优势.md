# 探讨 Cursor 比其它编程助手的优势

最近我尝试了 Cursor，毫不犹豫地得出结论：**这是一个值得我为其付费的产品。**

## 什么是 Cursor？

Cursor 是基于 VSCode 二次开发的代码编辑器，深度融合了 AI 特性。

[🔗 Cursor 官网](https://www.cursor.com)

由于 VSCode 本身具备广泛的功能和插件，Cursor 因此拥有了坚实的基础，用户可以无缝导入 VSCode 的插件、配置和主题，甚至可以通过 Github 或 Microsoft 账号同步配置。

然而，如果你习惯于使用其他编辑器，Cursor 目前未提供适用于这些编辑器的 AI 插件，且部分插件可能与 Cursor 存在冲突。

![Cursor](https://bbtdd.com/img/67783384.webp)

## Cursor 是编辑器，而非插件

现有的 AI 编程助手竞争激烈，包括 Github Copilot、Amazon CodeWhisperer、字节的豆包 MarsCode、阿里的通义灵码、讯飞的 iFlyCode 等。

Github Copilot 曾是当之无愧的领导者，得益于 Github 丰富的代码库和微软提供的 Azure + OpenAI 模型。

Cursor 之所以选择作为独立编辑器而非插件，是因为它需要对 UI 有更多控制权，无法通过插件形式实现 Cursor Tab 等功能。

Cursor 在数据源和模型未有重大突破的情况下，凭借**对开发者习惯的深入观察**，赢得了广泛好评。

## Cursor 的优势是什么？

Cursor 通过以下方式直击用户痛点：

- **Codebase**：Cursor 在提问时自动加入当前代码库作为参考文档，展示视频中效果是你可以主动 **@特定文档** 来参考某段代码。首次提问时，Cursor 会完整扫描整个文件夹里的文件作为数据源支撑，简化了手工操作，更贴合实际开发环境。而“引用多段代码”“遵循现有写法”恰恰是开发者对 AI 最迫切的需求。
  
  例如，Vue 3 的语法中有两种写法 `<script>` 和 `<script setup>`，不同写法的代码在结构上有所不同。如果你不给出任何参考去问 ChatGPT，ChatGPT 可能会随机给出一种答案，也许就是你不想要的。而有了 Cursor，它总是可以借助 Codebase 用项目中更常用的那个写法来提供建议。

👉 [WildCard | 一分钟注册，轻松订阅海外线上服务](https://bbtdd.com/WildCard)