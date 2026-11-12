# EnglishDrill App 仓库

英语刷题助手（EnglishDrill）的安装包与自更新清单。

- `latest.json`：App 内置的更新清单（版本号、APK 直链、sha256、大小、更新说明）；
- `EnglishDrill-v*.apk`：每个版本的安装包，放在对应 `v<版本>` 的
  **Releases（发行版）** 附件里。

App 冷启动会自动读 `latest.json`，发现新版本就在首页顶部提示，点一下即可下载安装
（下载后自动 sha256 校验，最后用系统安装器确认）。

手动安装地址（手机浏览器打开，需 VPN）：
`https://github.com/woshinifather856-hue/english-drill-app/releases`

只放个人自用安装包，不含任何用户的真题/听力内容（内容包在另一个仓库）。
