# Photerest

经典风格的 Android 本地照片与视频浏览器，支持收藏、每日精选、可调液态玻璃与可选联网识图。**闭源，免费使用**；本仓库只提供下载、更新说明和反馈入口。

## 最新版本：2.2.1

[下载 APK](https://github.com/Max1426/Photerest/releases/download/v2.2.1/Photerest-2.2.1.apk) · [Release](https://github.com/Max1426/Photerest/releases/tag/v2.2.1) · [校验值](https://github.com/Max1426/Photerest/releases/download/v2.2.1/SHA256SUMS.txt) · [验证边界](VERIFICATION-2.2.1.md)

Android 8.0+，versionCode 32，应用 ID `com.photerest.app`。原有上拉菜单布局已恢复，普通菜单玻璃默认关闭，可在「设置 → 毛玻璃 → 上拉面板」开启；识图结果保留玻璃。按钮与上拉面板分别保存折射、模糊、明暗和颜色等参数。

Google / 百度识图均在用户确认后上传照片缩放副本，并消耗一次共享额度；已保存的相同内容、相同引擎结果免费查看，手动刷新需再次确认。额度是服务端所有用户共享，并非每台手机单独拥有。常规图库浏览无需上传照片。

液态折射需要 Android 13+；Android 12 使用实时毛玻璃，Android 8–11 使用半透明遮罩。2.2.1 按用户要求仅构建，尚未进行本版真机及完整运行验收。

## Alpha

[Photerest Alpha](https://github.com/Max1426/Photerest-Alpha) 是独立的 Apache-2.0 开源 Material 实验版，可与经典版并排安装。当前经典版未加入本地 AI 模型中心。

[更新记录](CHANGELOG.md) · [博客页面更新交接](docs/BLOG-HANDOFF-2026-11-22.md) · [许可](LICENSE) · [第三方声明](THIRD_PARTY_NOTICES.md)
