# AntBot 更新发布通道（Releases）

本仓库是 **搬运蚁（AntBot）** 的统一发布仓库，源码仓库（`cxcboss/AntBot`）为私有，这里只放更新产物。

## 内容

| 类型 | 位置 | 说明 |
|------|------|------|
| **App 更新** | Releases（tag `vX.Y.Z`） | mac zip（`antbot-macos-arm64.zip`）+ win exe（`AntBot-<版本>-win-x64.exe`），App 内"检查更新"自动检测 |
| **浏览器插件更新** | Releases（tag `plugin-vX.Y.Z`） | 插件 zip，App 启动时自动更新 |
| **远程页面热更新** | 本仓库 `main` 分支 | `version.json` + `remote-ui/index.html` + `hub/index.html`，App 启动自动下载 |

## 发布规则

详见 AntBot 源码仓库 `docs/release-guidelines.md`（9 进制版本号、资产命名、checklist）。
