# 游戏回录

本仓库提供安装包下载和应用更新信息。

[下载最新版](https://github.com/YunsVoid/game-replay-updates/releases/latest)

## 发布更新

1. 使用同一发布证书签名新 APK，上传到 Releases。
2. 修改根目录 `version.json` 的 `versionName`、`url`、`note`。
3. 版本号按数字段比较，例如 `1.0.10` 大于 `1.0.9`。不需要在此填写数字版本代码。

公告继续在 [gra/announcement.json](https://github.com/YunsVoid/gra/blob/main/announcement.json) 维护。

1.0.2 及更早安装包仍使用旧更新地址，需要手动安装本仓库版本后接入这里的更新信息。
