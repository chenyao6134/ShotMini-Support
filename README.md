# ShotMini / 小截 技术支持

最后更新：2026-06-05

ShotMini（中文名：小截）是一款轻量的 macOS 截图工具，支持区域截图、窗口截图、截图标注、OCR 文字识别、钉图、滚动截图、GIF 录制和屏幕录制等功能。

如果你在使用 ShotMini 时遇到问题，可以通过以下方式联系支持：

- 支持邮箱：chenyao6134@gmail.com
- GitHub Issues：[https://github.com/chenyao6134/TinyShot/issues](https://github.com/chenyao6134/ShotMini-Support/issues)

## 功能概览

- 区域截图：拖拽选择屏幕区域，或点击窗口进行截图。
- 标注编辑：支持矩形、箭头、文字、高亮、模糊、马赛克、编号、水印、裁剪等工具。
- OCR 文字识别：使用 Apple Vision 在本机识别截图中的文字，支持中文、英文、日文等语言配置。
- 钉图：将截图固定在屏幕上，便于对照查看。
- 自动保存与剪贴板：可设置截图后自动复制到剪贴板，或保存到指定文件夹。
- 高级功能：滚动截图、GIF 录制、屏幕录制可通过订阅或终身购买解锁。
- AI 功能：可选功能。只有在用户主动配置 OpenAI API Key 并点击 AI 分析相关按钮时，才会调用 OpenAI API。

## 权限说明

ShotMini 需要部分 macOS 系统权限才能正常工作：

- 屏幕录制权限：用于截取屏幕内容、录制视频、录制 GIF 和滚动截图。
- 辅助功能权限：用于全局快捷键和部分交互控制，使截图快捷键在其他应用中也能可靠触发。
- 文件访问权限：仅用于保存截图、GIF 或视频到用户选择的文件夹。
- 剪贴板访问：用于将截图或 OCR 结果复制到剪贴板。

你可以在 macOS 的“系统设置”中管理这些权限：

- 系统设置 > 隐私与安全性 > 屏幕录制
- 系统设置 > 隐私与安全性 > 辅助功能

## 常见问题

### 截图无法开始或截图内容为空

请确认 ShotMini 已获得“屏幕录制”权限。授权后，如系统要求重启应用，请退出并重新打开 ShotMini。

### 全局快捷键不生效

请确认 ShotMini 已获得“辅助功能”权限。如果快捷键被其他应用或 macOS 系统快捷键占用，可以在 ShotMini 设置中更换快捷键。

### OCR 未识别到文字

请确认截图清晰、文字没有被严重压缩或遮挡。你也可以在设置中调整 OCR 识别语言。

### 截图没有保存到指定位置

请确认“自动保存到磁盘”已开启，并且保存位置仍然可访问。如果移动或删除了原保存文件夹，请在设置中重新选择保存位置。

### 如何恢复购买

打开 ShotMini 设置 > 高级功能，点击“恢复购买”。购买和订阅由 Apple App Store 处理，并绑定到当前 Apple ID。

### 如何申请退款

App Store 购买和订阅退款由 Apple 处理。请访问 Apple 的“报告问题”页面：https://reportaproblem.apple.com/

## 隐私与数据

ShotMini 默认在本机处理截图、标注、保存、OCR 和历史记录。截图、GIF、视频和 OCR 结果不会由应用主动上传到开发者服务器。

如果用户启用 AI 功能并配置 OpenAI API Key，ShotMini 会在用户主动点击 AI 分析、总结、表格提取、代码提取等功能时，将所选图片或文本发送给 OpenAI API 进行处理。该功能是可选的，未配置 API Key 时不可用。

## App Store 审核说明

- 应用名称：ShotMini / 小截
- 应用类别：工具
- 主要用途：macOS 截图、标注、OCR、钉图、滚动截图、GIF 录制和屏幕录制
- 账号要求：无需注册账号即可使用基础功能
- 内购说明：订阅或终身购买用于解锁滚动截图、GIF 录制、屏幕录制等高级功能
- 权限用途：屏幕录制用于截图与录制；辅助功能用于全局快捷键；文件权限用于保存到用户选择的位置
- 第三方服务：OpenAI API 仅用于可选 AI 功能，且需要用户自行提供 API Key

---

# ShotMini Technical Support

Last updated: 2026-06-05

ShotMini is a lightweight macOS screenshot utility for area capture, window capture, annotation, OCR, pinning images on screen, scrolling capture, GIF recording, and screen recording.

For support, please contact:

- Support email: TODO: replace with your support email
- GitHub Issues: https://github.com/chenyao6134/TinyShot/issues

## Features

- Area and window screenshots.
- Annotation tools, including rectangle, arrow, text, highlight, blur, mosaic, numbering, watermark, and crop.
- Local OCR powered by Apple Vision, with configurable recognition languages.
- Pin screenshots on screen for quick reference.
- Auto-copy and optional auto-save to a user-selected folder.
- Premium features: scrolling screenshots, GIF recording, and screen recording.
- Optional AI features using a user-provided OpenAI API key.

## Permissions

ShotMini may request these macOS permissions:

- Screen Recording: required for screenshots, GIF recording, video recording, and scrolling screenshots.
- Accessibility: required for reliable global shortcuts and interaction handling.
- File access: used only to save screenshots, GIFs, and videos to folders selected by the user.
- Clipboard access: used to copy screenshots or OCR results when requested or configured.

Permissions can be managed in macOS System Settings:

- System Settings > Privacy & Security > Screen Recording
- System Settings > Privacy & Security > Accessibility

## Troubleshooting

### Screenshots do not start or appear blank

Please make sure ShotMini has Screen Recording permission. After granting permission, quit and reopen the app if macOS asks you to do so.

### Global shortcuts do not work

Please make sure ShotMini has Accessibility permission. If another app or macOS shortcut uses the same keys, change the shortcut in ShotMini settings.

### OCR does not find text

Use a clear screenshot and make sure the target text is not too small, blurred, or covered. You can also adjust OCR recognition languages in settings.

### Files are not saved

Make sure auto-save is enabled and the selected save folder is still available. If the folder was moved or deleted, choose a new save location in settings.

### Restore purchases

Open ShotMini Settings > Advanced, then click Restore Purchases. Purchases and subscriptions are processed by Apple and associated with your Apple ID.

### Refunds

App Store purchases and subscription refunds are handled by Apple. Visit https://reportaproblem.apple.com/

## Privacy

ShotMini processes screenshots, annotations, local OCR, saved files, and history on the user's Mac by default. The app does not upload screenshots, GIFs, videos, or OCR results to a developer server.

If the user enables AI features and provides an OpenAI API key, ShotMini sends the selected image or text to the OpenAI API only when the user explicitly clicks an AI action such as analyze, summarize, table extraction, or code extraction. This feature is optional and unavailable without an API key.

## App Store Review Notes

- App name: ShotMini / 小截
- Category: Utilities
- Main purpose: macOS screenshot capture, annotation, OCR, pinned images, scrolling screenshots, GIF recording, and screen recording
- Account requirement: no account is required for basic use
- In-app purchases: subscriptions and lifetime purchase unlock advanced features
- Permissions: Screen Recording for capture and recording, Accessibility for global shortcuts, file access for user-selected save locations
- Third-party service: OpenAI API is used only for optional AI features and requires the user's own API key
