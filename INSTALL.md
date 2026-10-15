# 页间 · Pageglade 1.1.1 安装说明

## 适用范围

Apple Silicon Mac（M1 及后续），macOS 14+。当前没有 Intel 安装包，也未上架 App Store。

## 下载与校验

在 [1.1.1 发布页](https://github.com/yuwang4321/Pageglade/releases/tag/v1.1.1) 的 Assets 中下载 `Pageglade-1.1.1-arm64.dmg` 和 `Pageglade-1.1.1-arm64.dmg.sha256`。不要用自动生成的 Source code 压缩包安装应用，它们只包含当前仓库的介绍和发行资料。

SHA-256：
```text
53409cc513d3eae0732bcc63c89e79e61a1a25a95d0d8305805050137e6b714b  Pageglade-1.1.1-arm64.dmg
```

自行校验时，可在终端输入 `shasum -a 256` 并将下载的 DMG 拖入终端，核对结果。

## 安装或升级

1. 建议在旧版应用设置中导出阅读数据备份；原始书籍另行保管，备份不包含原书和缓存。
2. 退出已运行的 Pageglade。
3. 打开 DMG，将 Pageglade 拖入 Applications；已有版本选择替换。
4. 从 Applications 打开应用。替换程序不会主动清空书库、历史、书签、摘录和阅读设置。

本版未进行 Developer ID 发布签名或 Apple 公证。若系统提示开发者无法验证，请先确认来源与校验值，再参考 [Apple 官方说明](https://support.apple.com/102445)，在“系统设置 → 隐私与安全性”查看可用打开选项。无需关闭系统安全保护。若提示损坏或校验不一致，请重新下载。

## 阅读与摘录

- 导入入口可选择文件或文件夹；默认设置用于新书，阅读中调整后记住本书配置。
- 摘录页展示文字、图片及批注；摘录集单独展示。新摘录默认沿用书籍标签，支持多标签任一/全部筛选。集合保存后保持固定内容，创建时切换标签会取消不匹配勾选。
- 摘录瀑布流保留图片比例，支持拖动及键盘排序；摘录集支持 PDF、EPUB、Markdown 导出。
- 放大镜：**⌘⇧M** 开关，**⌥＋滚轮** 调整倍率，单击固定或继续跟随。可“保存放大区域”，也可使用“原页圈选”；保存或取消后恢复镜片。
- 沉浸阅读工具栏可用鼠标靠近边缘或 Tab 唤出。摘录期间暂停误触唤出；Esc 优先关闭摘录弹窗或取消圈选。
- 古籍默认20列、中央鱼尾版心；每叶稳定随机出现1～3种印章。
- 实际翻页/滚动后自动在读，自然读到末尾前台停留约10秒后已读，支持撤销；手动状态优先，可恢复自动判断。
- 应用设置内统一提供使用说明，弹窗顶部关闭按钮保持可见。

## 数据与组件

书籍副本、阅读记录与设置保存在本机。清理生成缓存不删除源文件；移出书库前请备份需要保留的阅读记录与摘录。本地 DMG 内置 calibre，许可与对应组件源码位于 DMG 的“开源组件”目录，无需另行安装。Pageglade 应用源码未公开。复杂文件可能存在兼容性问题；不支持 DRM、OCR 或云同步。

## English installation summary

Download the DMG from the [release Assets](https://github.com/yuwang4321/Pageglade/releases/tag/v1.1.1), verify its SHA-256, quit the old app and drag Pageglade into Applications. Requires Apple Silicon and macOS 14+. Back up reading data and keep original books separately. This build is not Developer ID signed or notarized; verify the source and follow Apple’s opening guidance without disabling system security protections.
