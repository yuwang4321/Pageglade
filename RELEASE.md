页间 1.6.6 将近期的阅读、摘录和书库改进整合为一个正式版本。电子书、PDF 与漫画仍共用本地书库，免费使用，无需注册阅读账号。

## 下载

- 安装包：**Pageglade-1.6.6-arm64.dmg**（本页 Assets）
- 适用：**Apple Silicon Mac（M1 及后续），macOS 14+**；暂无 Intel 安装包。
- 版本：**1.6.6 / build 37**。
- 退出旧版后，将 DMG 中的 Pageglade 拖入 Applications 并替换。更新程序不会主动清空原有阅读数据；建议升级前在应用设置中备份阅读数据。

## 新功能与体验改进

### 摘录与摘录集

- 主页提供独立的「摘录」与「摘录集」入口，文字、图片和想法均可保存、整理和重读。
- 摘录默认沿用来源书籍的现有标签，无需另建一套标签；保存时可自行调整。
- 支持多标签「匹配任一／包含全部」筛选，多选摘录、加入已有摘录集，以及集合内拖动排序。
- 摘录集可导出 **PDF、EPUB、Markdown**；包含图片的 Markdown 使用 ZIP 携带图片文件。导出保留内容顺序、来源与编号批注。
- 「查看原文」支持文字或图片来源区域标记，并可返回摘录集原位置；旧摘录或无法精确匹配时明确提示降级定位。
- 图片摘录使用一个保存入口，想法选填；文字操作明确为「复制文字」。

### 专注阅读

- TXT 与可重排电子书支持按屏分页；PDF 和漫画保留原页布局。
- 沉浸工具栏精简为单行图标：翻页、进度、书签、文字摘录、图片摘录、收藏和退出。悬停显示名称，闲置时隐藏。
- 支持中文、英文与跟随系统的界面语言，书籍原文及用户内容不翻译。
- 保留多文件标签页、字体与缩放设置、黑白水墨主题，以及古籍竖排与纸张纹理。

### 书库整理与阅读状态

- 首页直观显示「未读／在读／已读」。仅打开新书保持未读，实际翻页或滚动正文后进入在读。
- 自然读到末尾并在前台停留约 10 秒后自动标记已读，支持撤销；直接跳到末尾、恢复位置或调整排版不触发读完。
- 手动状态优先，可在书籍操作中「恢复自动判断」。阅读状态表示进度，不保证每一页都被实际读过。
- 书籍次要操作集中到「···」与右键菜单；菜单宽度缩至 160px，并避开窗口边界。
- 新导入区采用与 App 一致的淡色放大 Logo，突出选择文件；标签列表独立滚动。
- 阅读数据支持本地备份与恢复；备份不包含原始书籍及生成缓存，原文件请另行保管。

## 重点修复

- **1.6.6：** 创建摘录集切换标签或匹配方式后，取消不匹配内容的勾选；候选列表仅显示匹配摘录，保存前再次校验，避免混入其他标签内容。
- **1.6.5：** 修复沉浸图片摘录靠近底部时误唤出工具栏；捕获排除工具栏和界面提示，Esc 优先取消圈选，保存或取消后保持沉浸阅读。
- **1.6.4：** 新文字、图片摘录及页批注默认继承来源书籍标签。
- **1.6.3：** 摘录与摘录集分开显示；修复隐藏选中项和失效标签影响筛选的问题，调整标签编辑按钮与滚动条间距。
- **1.6.2：** 修复书籍菜单被侧栏或滚动区域遮挡，统一沉浸图标按钮，并恢复首页阅读状态的直观显示。
- 本轮迭代还改善 TXT 页面起始显示、来源定位、图片摘录保存、历史布局及长文件名展示。

## 安装、组件与限制

- 本版未进行 Developer ID 发行签名或 Apple 公证，未上架 App Store。请先核对来源和校验信息，参阅 [安装说明](https://github.com/yuwang4321/Pageglade/blob/main/INSTALL.md)。无需关闭系统安全保护。
- 本地 DMG 仍内置 calibre 组件，Kindle 格式直接解析，不生成 EPUB；FB2 在本地转换。组件许可及对应源码随 DMG 提供。
- 不支持 DRM、KFX、DJVU、CHM、AZW4；没有 OCR 或云同步。扫描页不提供可搜索正文，复杂排版和损坏文件可能有兼容性问题。
- EPUB/Kindle 的进度跳转按原章节，TXT 按屏分页模式按屏，PDF/漫画按原页。短到无法翻页或滚动的单页文件可手动标记已读。
- 摘录集为固定内容集合，保存后不会随标签变化自动增删。使用或导出摘录时，请遵守原内容的版权与使用许可。

## 校验与验证

SHA-256：

```text
398eb5e773cd965235e0bfe57b9ff2f2296bf078f710de1d0aab3021f77662f1  Pageglade-1.6.6-arm64.dmg
```

1.6.6 摘录集筛选完成 6 项原生隔离检查与 4 项构建相关检查；安装包与应用完整性校验通过。近期功能均有针对性验证，但不代表所有格式、所有书籍都经过完整回归。

## English highlights

- A free, local macOS reader for ebooks, PDFs and comics, with Chinese/English interface options.
- Text and image excerpts, shared tags, ordered excerpt collections, and PDF/EPUB/Markdown exports.
- A compact immersive toolbar, visible reading states, automatic completion with undo, and local reading-data backup.
- Fixes collection tag filtering, clipped book menus, and unwanted toolbar activation during image capture.
- Requires Apple Silicon and macOS 14+. This build is not Developer ID signed or notarized; DRM, OCR and cloud sync are not supported.

作者：**TaylorWang**。反馈请通过 [Issues](https://github.com/yuwang4321/Pageglade/issues)，附应用版本、macOS 版本、文件格式及复现步骤；请不要公开上传未经授权的完整书籍。
