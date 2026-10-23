<p align="center"><img src="assets/icon.png" width="100" alt="IINB 图标"></p>

# IINB

**为逐个审阅本地视频定制的 macOS 播放器。**

![产品介绍](assets/banner.svg)

[![下载](https://img.shields.io/badge/下载-DMG-brightgreen)](https://github.com/jhtnba/iinb/releases/latest) [![版本](https://img.shields.io/badge/版本-1.5.0-blue)](https://github.com/jhtnba/iinb/releases) [![系统](https://img.shields.io/badge/平台-macOS-black)](docs/INSTALL.md)

[下载应用](https://github.com/jhtnba/iinb/releases/latest) · [使用方法](docs/GUIDE.md) · [更新记录](CHANGELOG.md) · [常见问题](docs/FAQ.md) · [反馈问题](https://github.com/jhtnba/iinb/issues/new/choose)

## 为谁准备

为逐个审阅本地视频定制的 macOS 播放器。 如果你希望在 Mac 上完成本地视频逐个审阅，可以从当前版本开始尝试。

## 主要功能

| 功能 | 具体用途 |
|---|---|
| 独立控制条 | 底部控制条单独占用空间，保持可见，不叠加在视频画面上。 |
| 播放列表独占空间 | 列表打开时视频使用剩余区域，支持调宽与保持展开。 |
| 多种排序 | 按名称、路径、时长、文件大小，以及有无 Finder 标签排序。 |
| 右侧信息列 | 按大小排序显示大小；按标签排序显示标签；其他排序显示时长。 |
| 时长持久缓存 | 后台读取完整播放列表，缓存保存到内置磁盘，文件变化后重新读取。 |
| 审阅工作流 | 配合审阅标记插件，手动标记或切换文件时更新 Finder 标签。 |

## 下载与安装

当前定制版本基于 IINA 1.5.0（build 180）。面向 Apple Silicon，要求 macOS 12 或更新版本。

1. 从 [Releases](https://github.com/jhtnba/iinb/releases/latest) 下载 `IINB-1.5.0-macOS.dmg`。
2. 打开 DMG，将 App 拖入“应用程序”。
3. 审阅按钮需要另外安装同一 Release 中的审阅标记插件。

每次公开发布同时提供对应的定制源码包、构建说明和插件。源码包作为 Release 附件，不把开发目录提交到仓库。

## 第一次使用

1. 在“设置 → 用户界面 → 播放控制条”选择“底部”。
2. 打开一个视频，将其他视频加入播放列表；双击列表项播放，单击只选中。
3. 通过列表排序菜单选择时长、大小或标签；有无标签分组与标签文字无关。

[查看完整操作指南 →](docs/GUIDE.md)

## 使用前须知

- 基于 IINA 1.5.0 修改，不是 IINA 官方发布或官方支持版本。
- 审阅按钮需要配套插件；单独安装 App 不等于插件已启用。
- 关闭窗口和退出不会自动计入审阅；切换视频和手动完成仍按插件规则计数。
- 删除按钮将文件移到废纸篓；删除最后一项停止，不回到上一项。
- 不通过官方更新覆盖定制版，升级需下载新的定制构建。
- 保留原作者版权及 GPLv3 许可证；公开分发需提供对应源码获取方式。

## 问题反馈

通过 [Issues](https://github.com/jhtnba/iinb/issues/new/choose) 描述复现步骤、macOS 版本、应用版本和预期结果。截图请遮挡个人路径、用户名和文件内容；不要提交密码、令牌或原始私人文件。

## 更多应用

[咪咪](https://github.com/jhtnba/mimi) · [IINB](https://github.com/jhtnba/iinb) · [拾回](https://github.com/jhtnba/shihui) · [应用总览](https://github.com/jhtnba/mac-apps)

本页面只列出已有资料能核实的功能，不把计划功能写成已实现；未做过的兼容性和交互测试不作保证。
