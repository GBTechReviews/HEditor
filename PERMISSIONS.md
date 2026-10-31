# HEditor 绘影: Permissions and data / 权限与数据

Updated and effective / 更新与生效日期: 2026-10-31

Developer / 开发者: Griffith Rhys Bowen (GBTechReviews)

Contact / 联系方式: huaweiproreview@gmail.com

## English

### Personal information processing list: selected photos

The HarmonyOS Photo Picker grants access only to photos you select. HEditor reads their pixels and embedded metadata locally, and keeps private copies for drafts. The app does not request READ_IMAGEVIDEO or blanket library access.

### Saving and sharing

A system SaveButton grants each Gallery save. Sharing uses the system share sheet only when requested. The app does not need a camera, microphone, location or contacts permission.

### Optional vibration

ohos.permission.VIBRATE provides feedback while you use editing controls. Switch Haptic Feedback off in Settings to stop it.

### Clipboard and local storage

Copy actions write selected text to the clipboard. There are no background clipboard reads. Drafts, edit history, source copies, settings and Pro ownership remain in private app storage. Clear that storage or uninstall to remove them; Gallery exports and system backups are separate.

### Network and system capabilities

The app requests no INTERNET permission and contains no cloud-upload client, advertising or analytics SDK. Device subject segmentation is used only when you request it. Browser links, email, system backups and the operating system have separate data practices.

### Third-party personal information sharing list

No automatic developer-server or third-party SDK sharing. When you choose Share, the selected receiving app gets the export. When you open a website, its host receives the normal browser request, not your photo collection. Optional support messages and external purchases are described separately in the Privacy Policy.

## 简体中文

### 个人信息处理清单：所选照片

HarmonyOS 照片选择器仅授予对您主动选择照片的访问权限。HEditor 在本地读取像素和内嵌元数据，并保留草稿所需的私有副本。应用不申请 READ_IMAGEVIDEO 或整库访问权限。

### 保存与分享

保存至图库时使用系统保存按钮逐次授权。仅在您主动请求时打开系统分享面板。应用无需相机、麦克风、定位或通讯录权限。

### 可关闭的振动

ohos.permission.VIBRATE 用于编辑控件的触觉反馈。可在设置中关闭 Haptic Feedback（触觉反馈）。

### 剪贴板与本地存储

复制操作将所选文字写入剪贴板，不在后台读取剪贴板。草稿、历史、原图副本、设置及 Pro 标记保存在应用私有存储中。清除应用存储或卸载可删除这些数据；图库导出及系统备份需另行处理。

### 网络与系统能力

应用不申请 INTERNET 权限，不包含云上传客户端、广告或分析 SDK。仅在您请求时使用设备主体分割功能。浏览器链接、邮件、系统备份及操作系统有各自的数据处理规则。

### 第三方共享个人信息清单

不存在自动向开发者服务器或第三方 SDK 共享的行为。您主动分享时，指定接收应用会收到导出文件；您打开网站时，网站托管方收到正常浏览器请求，而非照片库。可选支持消息和外部购买信息在隐私政策中另行说明。
