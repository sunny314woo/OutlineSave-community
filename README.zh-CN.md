**语言切换：** [简体中文](./README.zh-CN.md) · [English](./README.md) · [Español](./README.es.md) · [日本語](./README.ja.md) · [Français](./README.fr.md)

# OutlineSave — ChatGPT Outline, Search & Export to HTML & PDF（社区版）

OutlineSave 是一款帮助用户整理 AI 长对话的浏览器扩展：提供目录导航、搜索、标注和导出，让聊天记录成为方便查找、复习和保存的知识内容，而不必一遍遍向上滚动寻找旧回答。

**本仓库提供的是早期、功能受限、源码可查看的 ChatGPT 社区演示版**，不是当前商业正式版的完整源码，也不代表最新线上功能实现。完整的 OutlineSave 扩展通过 Chrome 网上应用店单独发布。

**[从 Chrome 商店安装 OutlineSave 正式版](https://chromewebstore.google.com/detail/opbngifmlnoahbhjhgmngkggedlofddj)** · **[在线体验 HTML 导出效果](https://wisteriasoftware.uk/demo)** · **[查看产品介绍](https://wisteriasoftware.uk/outline-pro)**

![ChatGPT Outline 社区版演示](./jump-ezgif.com-crop.gif)

> **社区演示版限制：** 只有前 15 条目录支持点击跳转。下文提到的搜索、标注、导出等完整功能属于需要另外安装的 OutlineSave 正式版，而非本仓库代码。

## 社区演示版包含什么？

- 为 ChatGPT 对话生成可点击的目录
- 对话新增内容时自动更新目录
- 目录侧边栏支持左右位置切换
- 体验长对话目录导航的基本交互

仅前 15 条目录可跳转，是**本仓库演示版**的限制，不代表 OutlineSave 正式版的目录长度限制。

## 了解 OutlineSave 正式版

正式版支持 **ChatGPT、Gemini、Claude 和 DeepSeek** 的对话。不同 AI 平台的具体功能和交互方式可能有所差异。

### ChatGPT Outline：长对话的两级目录导航

正式版提供两级目录：用户提问为一级，AI 回答中的标题为二级。可搜索目录标题，并跳转到对应的对话位置，不必逐条翻找。

对于超长的 ChatGPT 对话，目录可以逐步加载。加载时间和完整程度仍取决于原平台及对话情况。

### Search：找回需要的内容

在在线对话中搜索用户问题与 AI 回答的目录标题；导出为 HTML 后，还可以对保存的正文进行全文搜索。**目录标题搜索和离线 HTML 全文搜索是不同能力**，不要混为一谈。

### Export to HTML：把对话保存成离线知识页

将聊天记录导出为独立、适配不同屏幕的 HTML 文件。保存后可直接在本地打开，无需重新进入 ChatGPT，也不必等待原始长对话重新加载。

HTML 导出可以保留：

- 两级目录与跳转导航
- 全文搜索
- 已有高亮、下划线、备注和书签
- 书签及高亮颜色筛选
- 代码块、数学公式和 Mermaid 流程图

**[在线体验可交互的 HTML 导出文件](https://wisteriasoftware.uk/demo)**

### PDF 导出

PDF 导出功能正在开发中。**截至本次 README 更新，PDF 尚未随 Chrome 商店正式版发布。** 当前可用的功能请以 [Chrome 商店页面](https://chromewebstore.google.com/detail/opbngifmlnoahbhjhgmngkggedlofddj) 为准。

### 高亮、备注、书签、Markdown 和 JSON

正式版可用四种颜色高亮重点、添加下划线与备注、收藏重要章节，也支持 Markdown 和 JSON 导出。

### 本地优先处理对话

OutlineSave 默认在本地处理 AI 对话内容，不会把聊天正文上传至 Wisteria Software 自有服务器，也不需要注册 OutlineSave 账号。激活及必要运行数据可能用于授权和产品运营；Google Drive 备份由用户主动触发，并将所选备份数据保存到用户自己的云盘。详情参见[隐私政策](https://wisteriasoftware.uk/privacy)。

### 可选：配合 Inbox Local 管理知识

[Inbox Local](https://github.com/sunny314woo/wisteria-suite/tree/main/apps/inbox-local) 是另一个本地优先的知识管理工具，可用于整理从 OutlineSave 导出的 Markdown 和富 HTML 内容。它是可选的配套产品，不属于本仓库的社区演示版。

## 社区演示版与 OutlineSave 正式版对比

| 功能 | 本仓库社区演示版 | OutlineSave 正式版 |
|---|---|---|
| ChatGPT 对话目录 | 支持 | 支持 |
| 点击目录跳转 | 仅前 15 条 | 完整目录导航 |
| 两级目录 | 不包含 | 支持 |
| 目录标题搜索 | 不包含 | 支持 |
| 导出 HTML 后全文搜索 | 不包含 | 支持 |
| 高亮、下划线、备注与书签 | 不包含 | 支持 |
| 离线 HTML 导出 | 不包含 | 支持 |
| Markdown、JSON 导出 | 不包含 | 支持 |
| Gemini、Claude、DeepSeek | 不包含 | 支持 |
| PDF 导出 | 不包含 | 开发中，发布状态以商店为准 |

## 常见问题 FAQ

### 如何给 ChatGPT 长对话添加目录？

可在 [Chrome 商店](https://chromewebstore.google.com/detail/opbngifmlnoahbhjhgmngkggedlofddj)安装 OutlineSave 正式版。本仓库提供的演示代码仅支持前 15 条目录跳转。

### 可以搜索 ChatGPT 长对话吗？

正式版可搜索在线对话的目录标题；导出 HTML 后，还可以全文搜索保存的对话内容。

### 可以把 ChatGPT 对话导出为离线 HTML 吗？

可以。正式版可导出独立、响应式的 HTML 文件，保留目录、全文搜索及支持的已有标注。本地阅读时无需重新加载 ChatGPT 对话。

### OutlineSave 会上传我的 AI 对话吗？

对话正文默认在本地处理，不会上传到 Wisteria Software 自有服务器。手动备份和产品运行服务有各自的数据处理流程，详见[隐私政策](https://wisteriasoftware.uk/privacy)。

### OutlineSave 免费吗？

正式版提供免费基础功能，也有试用和付费选项。导出额度及许可证权益可能调整，请以[官方产品页面](https://wisteriasoftware.uk/outline-pro)为准。

### 导出的 HTML 能在手机上阅读吗？

可以。HTML 文件适配不同屏幕，传到手机后可以使用兼容的浏览器打开，不需要重新加载原始 ChatGPT 对话。

## 在本地运行社区演示版

1. 在 Chrome 打开 **chrome://extensions**。
2. 开启「开发者模式」。
3. 点击「加载已解压的扩展程序」。
4. 选择本仓库文件夹。

## 许可证和源码说明

本仓库是**源码可查看的社区演示版**，采用 [LICENSE](./LICENSE) 中的自定义许可证，**不是 MIT 或 Apache-2.0 开源授权**。公开演示代码并不代表授予商业正式版、产品品牌、服务端系统等专有内容的使用权。详情见 [NOTICE](./NOTICE)。

**[从 Chrome 商店安装 OutlineSave](https://chromewebstore.google.com/detail/opbngifmlnoahbhjhgmngkggedlofddj)** · **[在线体验 HTML 导出效果](https://wisteriasoftware.uk/demo)**

**语言切换：** [简体中文](./README.zh-CN.md) · [English](./README.md) · [Español](./README.es.md) · [日本語](./README.ja.md) · [Français](./README.fr.md)
