# Composa 简体中文 Windows 便携版

基于 [dvdstelt/Composa](https://github.com/dvdstelt/Composa) 1.4.0 的社区汉化版本。Composa 是 [Compositor](https://github.com/robbietilton/Compositor) 的独立跨平台实现。本项目不是上游官方中文发行版。

## 下载和使用

**[下载中文版（Windows x64）](https://github.com/0505YZX/Composa-zh-CN/releases/download/v1.4.0-zh.1/Composa-1.4.0-zh-CN-win-x64.zip)** · [查看发布页面](https://github.com/0505YZX/Composa-zh-CN/releases/latest)

1. 解压整个 ZIP。
2. 双击 `启动中文版.bat`，或运行 `软件/composa.exe`。
3. Windows 10/11 x64，无需安装或另装 .NET。
4. 请保留完整软件文件夹。不要只拷贝 exe。

需要英文界面时运行 `启动英文界面.bat`。程序设置和恢复数据保存在解压后的 `软件/data` 中。

## 汉化内容

共 763 条简体中文译文，覆盖菜单、工具栏、参数、混合模式、历史记录、常用对话框和提示。部分第三方标签、模型名称、技术错误详情和作者信息可能仍为英文。

快捷键、用户图层名称和项目格式保留原有行为。项目使用 `.cmps`；可导出 PNG、JPEG 或 WebP。上游英文更新会覆盖汉化，本版默认关闭自动更新。

## 源码和重新编译

下载 Releases 中的 `Composa-1.4.0-zh-CN-source.zip`，将其中的“源码”目录解压到便携版根目录，与“软件”目录并列。关闭软件后，使用 .NET 10 SDK 运行“源码/重新编译.ps1”。仅运行软件不需要 SDK。

源码包包含完整修改后源码、763 条翻译、原有文件补丁和离线引用构建文件；构建会引用便携包随附的原版运行组件。

## 版本和验证

- 上游版本：1.4.0
- 上游提交：`86529d3b5355d28ddc28ec3db2e4de1d4d00f63b`
- 汉化日期：2026-10-07
- 已完成 16 项编辑流程检查及 Windows 启动检查，包括新建、绘画、撤销、项目保存/读取和 PNG 导出。
- 下载文件校验值见 Releases 中的 `SHA256SUMS.txt`。

## 作者和许可证

Composa 原作者：Dennis van der Stelt。原始 Compositor 作者/版权方：Robbie Tilton / Wonder Assembly LLC。

Composa 本体使用 MIT 许可，原作者版权及完整许可见 [LICENSE](LICENSE)。第三方运行组件及模型使用各自许可证，随程序保留完整的 `THIRD-PARTY-NOTICES.txt` 和 `ImageMagick-NOTICE.txt`。汉化改动随本项目采用 MIT 许可。
