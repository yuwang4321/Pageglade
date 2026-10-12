# 页间 · Pageglade

![页间 · Pageglade](banner.png)

免费的 macOS 本地阅读器。电子书、PDF、漫画共用一个书库，支持多种文件格式与类似 Kindle 的黑白水墨阅读主题。

作者 **TaylorWang**。无需注册阅读账号，书籍与阅读记录保存在本机。

## 下载与安装

**[下载最新正式版 1.6.6](https://github.com/yuwang4321/Pageglade/releases/tag/v1.6.6)** · [安装说明](INSTALL.md) · [完整更新记录](CHANGELOG.md)

适用于 **Apple Silicon Mac（M1 及后续）与 macOS 14+**，当前不提供 Intel 安装包。

下载发布页 Assets 中的 `Pageglade-1.6.6-arm64.dmg` 和 SHA-256 校验文件。退出旧版，将 DMG 中的 Pageglade 拖入 Applications 并选择替换。不要用自动生成的 Source code 压缩包安装应用。

本版未做 Developer ID 发行签名或 Apple 公证，也未上架 App Store。首次打开请核对来源，参考安装说明，无需关闭系统安全保护。

## 一个书库，持续阅读

- **电子书、PDF、漫画统一管理**：封面、标签、收藏、历史、继续阅读与多文件标签页。
- **多格式**：PDF、EPUB、TXT、无 DRM MOBI/AZW/AZW3/PRC，漫画压缩包和图片文件夹。
- **适合自己的显示方式**：单页/双页、翻页/滚动、按屏分页、缩放、字号、章节目录与缩略图。
- **专注阅读**：单行沉浸工具栏、黑白水墨主题、古籍竖排与稳定轮换纸纹。
- **中英文界面**：中文、英文或跟随系统；书籍原文不翻译。
- **轻量整理**：直观的未读/在读/已读状态，手动调整优先，本地阅读数据备份。

## 摘录与摘录集

保存文字、图片和想法，在独立摘录页统一回顾。新摘录默认沿用来源书籍标签，支持多标签任一/全部筛选。

多选内容创建摘录集，加入已有集合并拖动排序，重读时可查看原文并返回原位置。支持 **PDF、EPUB、Markdown** 导出；图片 Markdown 使用 ZIP 携带图片。

摘录与摘录集分别展示，集合保存后保持固定内容。1.6.6 修复创建过程中标签切换未取消不匹配勾选的问题，保存前再次校验。

## 1.6.6 正式发布

本次汇总 1.0.4 之后的阅读、摘录和书库更新：

- 摘录集独立入口、图片摘录、共享标签、排序与导出。
- 按屏分页、中英文界面和单行沉浸图标工具栏。
- 自动阅读状态与撤销，精简书籍操作菜单。
- 修复标签滚动条交互、菜单遮挡、图片捕获误唤出工具栏及集合筛选遗漏。

[查看发布说明](RELEASE.md)

## 支持格式与限制

- 电子书与文档：PDF、EPUB、TXT、无 DRM MOBI/AZW/AZW3/PRC。
- 漫画与图片：ZIP/CBZ、RAR/CBR、7Z/CB7、图片文件夹。
- 其他：FB2；HTML、RTF、DOCX 的文字读取，复杂排版可能丢失。

本地版内置 calibre：Kindle 直接解析正文、图片和封面，不转成 EPUB；FB2 本地转换。组件许可及对应源码随 DMG 提供，无需另行安装 calibre。

不支持 DRM、KFX、DJVU、CHM、AZW4，没有 OCR 或云同步。扫描页没有可搜索正文；复杂或损坏文件可能有兼容性问题。水墨为软件显示主题，不是电子墨水屏硬件，也不承诺护眼效果。

## English

Pageglade is a free local macOS reader for ebooks, PDFs and comics. It offers a shared library, Chinese/English interface, immersive reading, monochrome styling, text/image excerpts and ordered collections with PDF/EPUB/Markdown export.

Requires Apple Silicon and macOS 14+. The current DMG is not Developer ID signed or notarized. See [installation instructions](INSTALL.md) and [release notes](RELEASE.md).

## 反馈与仓库范围

欢迎通过 [Issues](https://github.com/yuwang4321/Pageglade/issues) 提交问题或建议，提供 macOS 版本、应用版本、文件格式、操作步骤与截图。请不要公开上传未经授权的整本书籍，可使用自制最小样例。

当前仓库提供介绍和发行资料，**不包含 Pageglade 应用源码**。免费使用不代表项目按开源许可证发布，第三方组件遵循各自许可证。

应用名称 Pageglade，中文品牌「页间」，Logo 使用繁体「頁間」。
