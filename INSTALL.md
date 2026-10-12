# 页间 · Pageglade 1.6.6 安装说明

## 适用范围

Apple Silicon Mac（M1 及后续），macOS 14+。当前没有 Intel 安装包，也未上架 App Store。

## 下载与校验

在 [1.6.6 发布页](https://github.com/yuwang4321/Pageglade/releases/tag/v1.6.6) 的 Assets 中下载：

- `Pageglade-1.6.6-arm64.dmg`
- `Pageglade-1.6.6-arm64.dmg.sha256`

不要下载自动生成的 Source code 压缩包用于安装，它们仅包含当前仓库的介绍和发行资料。

SHA-256：

```text
398eb5e773cd965235e0bfe57b9ff2f2296bf078f710de1d0aab3021f77662f1  Pageglade-1.6.6-arm64.dmg
```

需要自行校验时，在终端运行 `shasum -a 256` 并将下载的 DMG 拖入终端，核对结果与上面的值一致。

## 安装或升级

1. 升级前建议在旧版应用设置中导出阅读数据备份；原始书籍另行保管，备份不包含原书和缓存。
2. 退出已运行的 Pageglade。
3. 打开 DMG，将 Pageglade 拖入 Applications；已有版本选择替换。
4. 从 Applications 打开应用。替换程序不会主动清空书库、历史、书签、摘录和阅读设置。

本版未进行 Developer ID 发行签名或 Apple 公证。若系统提示开发者无法验证，请先确认 GitHub 来源与校验值；确认信任后，参考 [Apple 的打开应用说明](https://support.apple.com/102445)，在「系统设置 → 隐私与安全性」查看可用的打开选项。无需关闭 Gatekeeper、SIP 或其他系统安全保护。若出现损坏提示或校验不一致，请重新下载，不要直接跳过检查。

## 阅读与摘录

- 导入入口选择文件或文件夹。阅读设置采用全局默认，调整后记住本书配置。
- 「摘录」仅展示文字/图片摘录和批注；「摘录集」展示已保存集合。
- 新摘录默认沿用来源书籍标签，保存时可调整。创建集合时，单标签或多标签匹配只保留符合条件的候选与勾选项。
- 沉浸阅读底部图标工具栏可用鼠标靠近边缘或 Tab 唤出；图片捕获时暂时锁定，Esc 优先取消圈选。
- 自动状态：实际翻页/滚动后在读，自然到末尾前台停留约10秒后已读，支持撤销；手动设置优先，可恢复自动判断。

## 数据与组件

书籍副本、阅读记录与设置存放本机。清理生成缓存不删除源文件；移出书库会移除该书相关记录，请先导出或备份需要保留的摘录。

本地 DMG 内置 calibre 组件，无需额外安装；组件许可与对应源码位于 DMG 的「开源组件」目录。Pageglade 应用源码未公开。复杂书籍可能有兼容性问题；不支持 DRM、OCR 或云同步。

## English installation summary

Download the DMG from the release Assets, verify its SHA-256, quit the old app and drag Pageglade into Applications. Requires Apple Silicon and macOS 14+. Back up reading data before upgrading; book originals are not included in the backup. This build is not Developer ID signed or notarized. Verify the source and follow Apple's opening guidance; do not disable system security protections.
