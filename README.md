# Fullcoin TV 更新

适用于 Android 5.0 及以上电视、电视盒子，支持遥控器方向键。

[下载最新版](https://github.com/seanshigit/fullcoin-tv-updates/releases/latest)

- 通用安装包不含私人线路或密码。已有线路会在覆盖更新后保留；首次使用通用包需要导入自己的 AnyTLS 链接。
- 从 1.0.2 或更早的私人版本升级，请先安装并打开新的私人安装包一次，使线路保存到电视，再使用本更新通道。
- 打开应用时自动检查更新，并由 Android 定期在后台检查。非计费网络自动下载，回到应用后确认安装。也可在“设置”中检查、下载或安装更新。
- 安装会短暂关闭应用。系统可能要求允许 Fullcoin TV 安装应用，并确认安装；原先连接中的 VPN 会在更新完成后尝试恢复。
- 规则模式：中国大陆与其他公网流量走代理，局域网直连。

不知道架构时选择 universal；大多数新电视使用 arm64-v8a，旧 ARM 盒子使用 armeabi-v7a。

应用只接受原签名、正确包名和更高版本的 APK。发布页提供 SHA256SUMS.txt；稳定更新清单为 [update.json](https://github.com/seanshigit/fullcoin-tv-updates/releases/latest/download/update.json)。无需 GitHub 登录或访问令牌。

本程序基于 sing-box 1.14.4，使用 GPL-3.0-or-later 许可。每次发布附有不含私人输入的完整对应源码、构建说明和第三方许可。
