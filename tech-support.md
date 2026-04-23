# Trove 应用技术支持文档
## 文档概述
本文档为Trove模玩收藏管理应用的官方技术支持文档，旨在帮助用户全面了解应用功能、解决使用过程中遇到的各类问题，同时明确应用的技术架构、合规边界与用户权益。文档内容与应用《用户协议》《隐私政策》完全一致，若有内容冲突，以应用内最新版协议与政策为准。

## 一、应用基础信息
- **应用名称**：Trove
- **适用系统**：iOS 18.0及以上版本
- **支持设备**：iPhone、iPad（苹果官方正版未越狱设备）
- **分发渠道**：苹果App Store独家分发
- **核心架构**：纯本地离线运行，无自有/第三方服务器，无联网通信模块，零数据收集，仅通过苹果iOS原生iCloud框架提供可选同步服务，通过苹果官方IAP系统提供应用内购买服务

## 二、核心功能说明
1.  **藏品数字化管理**：支持录入模型、手办、成品模玩的全维度信息，搭配高清图片存储，为每件藏品建立专属数字档案，完整留存开箱、制作、改造、完工全流程内容。
2.  **制作过程全记录**：专属制作日志模块，可留存模型制作、改色、优化的全流程步骤、图片与心得，方便回溯与方案复刻。
3.  **收藏数据智能统计**：自动生成可视化数据报表，实时更新藏品总量、收藏价值、品类占比等核心数据，清晰呈现收藏全貌。
4.  **心愿清单管理**：可记录心仪藏品，规划购入节奏，辅助用户合理规划收藏计划。
5.  **多端数据同步**：可选开启苹果iCloud同步，实现iPhone、iPad多端数据无缝流转，通过苹果原生系统能力保障收藏档案安全。

## 三、常见问题FAQ
### （一）基础使用类
1.  **问：使用这个应用需要注册登录账号吗？**
    答：不需要。本应用无账号注册与登录体系，下载安装后即可直接使用全部核心功能，无需提供任何个人身份信息。
2.  **问：应用不联网可以使用吗？**
    答：可以。本应用全部核心功能均可在完全离线状态下使用，仅当您主动开启iCloud同步、使用应用内购买功能时，需要依赖苹果系统的相关网络服务。
3.  **问：如何添加我的第一件藏品？**
    答：打开应用后，在藏品主页点击「+」按钮，按页面提示录入藏品信息、上传相关图片，填写完成后点击保存即可。
4.  **问：我的藏品数据都存储在哪里？**
    答：您的所有藏品数据默认仅加密存储在您的iOS设备本地，全程不会离开您的设备；仅当您主动开启iCloud同步功能后，数据会通过苹果原生iCloud框架同步至您的个人iCloud账户存储空间，我们无法访问、获取您的任何数据。

### （二）数据同步类
1.  **问：如何开启iCloud同步？**
    答：您需要先在iOS系统设置中登录您的Apple ID，开启iCloud功能，随后在系统设置中找到Trove应用，开启「iCloud」权限，即可完成同步功能开启。开启后，系统将自动通过原生iCloud框架同步您的本地数据。
2.  **问：开启iCloud同步后，开发者能看到我的数据吗？**
    答：不能。iCloud同步过程完全由苹果iOS系统原生框架独立执行，应用本身无法拦截、读取、上传、篡改同步过程中的任何数据，也不参与任何数据传输环节，开发者无法访问、查看您存储在iCloud中的任何内容。
3.  **问：卸载应用后，我的数据会丢失吗？**
    答：若您未开启iCloud同步，卸载应用时，设备本地存储的全部应用数据将被永久自动删除，无法恢复；若您已开启iCloud同步，同步至iCloud账户的数据会被保留，重新安装应用并开启同账号iCloud权限后，可自动恢复数据。
4.  **问：换了新设备，如何转移我的藏品数据？**
    答：您可在旧设备开启iCloud同步，确保数据已完整同步至云端，在新设备登录同一个Apple ID，并在系统设置中开启Trove的iCloud权限，系统将自动同步您的全部藏品数据。

### （三）权限相关类
1.  **问：应用为什么需要申请相册/相机权限？**
    答：相册权限仅用于您从系统相册中选取藏品相关图片，存入应用本地数据库；相机权限仅用于您拍摄藏品相关图片，存入应用本地数据库。应用仅读取您主动选取的图片文件，不会读取、上传您相册内的其他内容，拍摄的图片仅存储在设备本地，不会上传至任何云端。
2.  **问：我关闭了权限，会影响应用的核心使用吗？**
    答：不会。相册、相机权限均为可选授权，关闭后仅无法上传/拍摄藏品图片，不影响藏品信息录入、数据统计等其他核心功能的正常使用。
3.  **问：应用会申请位置、通讯录、麦克风等其他权限吗？**
    答：不会。应用严格遵循「最小必要」原则申请系统权限，不会申请、获取任何与藏品记录核心功能无关的系统权限。

### （四）故障类
1.  **问：应用出现闪退怎么办？**
    答：您可先尝试关闭应用后台进程后重新打开；若仍闪退，可重启您的iOS设备后再次尝试；请确认您的设备系统版本为iOS 18.0及以上，且为正版未越狱系统；若以上操作均无法解决，可通过本文档末尾的联系方式向我们反馈。
2.  **问：iCloud同步失败/不同步怎么办？**
    答：请先确认您的Apple ID已正常登录iCloud，且iCloud有充足的存储空间；确认iOS系统设置中已为Trove开启iCloud权限；检查设备网络状态是否稳定；可尝试关闭iCloud权限后重新开启，或重启设备后再次尝试。iCloud服务由苹果公司独立运营，若持续异常，可联系苹果官方客服咨询。
3.  **问：藏品图片无法加载/上传怎么办？**
    答：请确认您已为应用开启相册/相机权限；确认图片文件未损坏，且设备存储空间充足；可尝试关闭应用后台后重新打开，再次上传图片。

## 四、应用内购买相关说明
1.  本应用的付费功能、永久版权益、订阅服务，全部通过苹果官方应用内购买（IAP）系统完成交易，所有支付流程、订单管理、自动续期、退款申请均由苹果公司负责处理。我们仅接收苹果官方反馈的购买状态，不会获取、存储您的任何支付信息、银行卡信息、订单详情。
2.  您通过苹果IAP系统购买的付费权益，仅可用于当前使用的设备及对应绑定的Apple ID账号，不得转让、出租、出借、分享给第三方。
3.  订阅服务将按您选择的周期，由苹果系统自动续期，除非您提前在Apple ID账号设置中手动关闭自动续期功能。因未及时取消续期导致的自动扣费，我们无法为您办理退费。
4.  所有内购相关的退款申请，均需通过苹果官方渠道提交，我们不直接处理任何退款事宜，也无法干预苹果官方的退款审核结果。

## 五、进阶故障排查指南
若您遇到应用使用异常，可按以下步骤依次排查，绝大多数问题均可通过以下操作解决：
1.  **基础重启**：关闭应用后台进程，等待10秒后重新打开应用，查看异常是否解决。
2.  **设备重启**：重启您的iPhone/iPad设备，重启完成后重新打开应用，排查系统临时缓存导致的异常。
3.  **系统与版本检查**：确认您的iOS系统版本符合应用运行要求，且应用已更新至App Store发布的最新版本。
4.  **权限与存储检查**：确认iOS系统设置中，已为应用开启所需的相关权限，且设备有充足的存储空间。
5.  **iCloud同步异常排查**：确认Apple ID登录状态正常，iCloud存储空间充足，可尝试重新开启应用的iCloud权限，触发系统重新同步。
6.  **重装应用**：若以上操作均无法解决，重装前请先确认已开启iCloud同步，且数据已完整同步至云端；随后卸载应用，从App Store重新安装，登录同一Apple ID并开启iCloud权限即可恢复数据。未开启iCloud同步的情况下，卸载应用将永久删除本地全部数据，无法恢复。

## 六、用户反馈指引
若您遇到无法通过上述内容解决的问题，或有功能优化建议、BUG反馈，可通过电子邮件联系我们，我们将在合理期限内给您回复。
- **联系邮箱**：rinkakumada@foxmail.com
- **反馈建议格式**：
  1.  您的设备型号（如：iPhone 15 Pro）
  2.  iOS系统版本（如：iOS 18.0）
  3.  应用版本号
  4.  问题的详细描述、复现步骤
  5.  相关问题的截图/录屏（可选）

## 七、隐私与合规说明
本应用严格遵循全球主流隐私法规与苹果App Store审核规则，恪守「零数据收集、全本地运行、用户绝对主控」的核心隐私原则，不集成任何第三方SDK、广告插件、统计分析工具，所有数据均由用户自主管理。
- 简体中文隐私政策：https://github.com/98Ahua/Trove/blob/main/privacy-policy.md
- 简体中文用户协议：https://github.com/98Ahua/Trove/blob/main/User-Agreement.md
- 英文隐私政策：https://github.com/98Ahua/Trove/blob/main/privacy-policy-en.md
- 英文用户协议：https://github.com/98Ahua/Trove/blob/main/User-Agreement-en.md

## 八、文档更新说明
本文档将根据应用功能迭代、法律法规更新、监管要求调整同步修订，最新版本将通过应用内公告、官方渠道同步更新。
- 文档最后更新日期：2026年4月

---

# Trove Technical Support Document
## Document Overview
This document is the official technical support document for the Trove model & figure collection management application. It is designed to help users fully understand the application's functions, solve various problems encountered during use, and clarify the application's technical architecture, compliance boundaries, and user rights. The content of this document is fully consistent with the application's **User Agreement** and **Privacy Policy**. In case of any conflict, the latest version of the agreement and policy in the application shall prevail.

## 1. Basic Application Information
- **Application Name**: Trove
- **Supported System**: iOS 18.0 and above
- **Supported Devices**: iPhone, iPad (genuine non-jailbroken Apple devices)
- **Distribution Channel**: Exclusively distributed via the Apple App Store
- **Core Architecture**: Purely local offline operation, no self-owned/third-party servers, no network communication module, zero data collection. Only provides optional sync service through Apple iOS native iCloud framework, and in-app purchase services through Apple's official IAP system.

## 2. Core Function Description
1.  **Digital Collection Management**: Support entering comprehensive information of scale models, figures, and finished models, with high-resolution image storage, to create an exclusive digital profile for each collectible, and fully retain the whole process from unboxing, building, customizing to final completion.
2.  **Full Build Process Logging**: Dedicated build journal module, which can save every step, photo and note of model building, painting and customization, for easy review and project reproduction.
3.  **Smart Collection Statistics**: Automatically generate visual data reports, real-time update core data such as total item count, collection value, and category breakdown, to clearly present the full picture of your collection.
4.  **Wishlist Management**: Record the items you want, plan your purchase timeline, and help users reasonably plan their collection journey.
5.  **Multi-device Data Sync**: Optional Apple iCloud sync is available to realize seamless data flow between iPhone and iPad, and ensure the security of your collection archive through Apple's native system capabilities.

## 3. Frequently Asked Questions (FAQ)
### (1) Basic Usage
1.  **Q: Do I need to register an account to use this application?**
    A: No. This application has no account registration or login system. You can use all core functions directly after downloading and installing, without providing any personal identity information.
2.  **Q: Can I use the application without an internet connection?**
    A: Yes. All core functions of this application can be used in a completely offline state. Only when you actively enable iCloud sync or use in-app purchase functions, you need to rely on the relevant network services of the Apple system.
3.  **Q: How do I add my first collectible?**
    A: After opening the application, click the「+」button on the collection homepage, enter the collectible information and upload relevant pictures as prompted on the page, and click Save after filling in.
4.  **Q: Where is my collection data stored?**
    A: All your collection data is only encrypted and stored locally on your iOS device by default, and will never leave your device throughout the process. Only when you actively enable the iCloud sync function, the data will be synced to your personal iCloud account storage space through Apple's native iCloud framework. We cannot access or obtain any of your data.

### (2) Data Sync
1.  **Q: How to enable iCloud sync?**
    A: You need to first log in to your Apple ID in the iOS system settings and enable the iCloud function. Then find the Trove application in the system settings, and enable the「iCloud」permission to complete the sync function activation. After enabling, the system will automatically sync your local data through the native iCloud framework.
2.  **Q: Can the developer see my data after enabling iCloud sync?**
    A: No. The iCloud sync process is completely executed independently by the native framework of Apple iOS system. The application itself cannot intercept, read, upload or tamper with any data in the sync process, nor participate in any link of data transmission. The developer cannot access or view any content you store in iCloud.
3.  **Q: Will my data be lost after uninstalling the application?**
    A: If you have not enabled iCloud sync, all application data stored locally on the device will be permanently and automatically deleted when the application is uninstalled, and cannot be recovered. If you have enabled iCloud sync, the data synced to your iCloud account will be retained, and will be automatically restored after you reinstall the application and enable iCloud permission with the same account.
4.  **Q: How to transfer my collection data when I get a new device?**
    A: You can enable iCloud sync on your old device to ensure that the data has been fully synced to the cloud. Log in to the same Apple ID on the new device, and enable Trove's iCloud permission in the system settings, the system will automatically sync all your collection data.

### (3) Permission Related
1.  **Q: Why does the application need to apply for photo library/camera permission?**
    A: The photo library permission is only used for you to select collection-related pictures from the system photo library and store them in the local database of the application. The camera permission is only used for you to take collection-related pictures and store them in the local database of the application. The application only reads the image files you actively select, and will not read or upload other content in your photo library. The pictures taken are only stored locally on the device, and will not be uploaded to any cloud.
2.  **Q: If I turn off the permissions, will it affect the core use of the application?**
    A: No. The photo library and camera permissions are optional authorizations. After turning off, you only cannot upload/take collection pictures, which will not affect the normal use of other core functions such as collection information entry and data statistics.
3.  **Q: Will the application apply for other permissions such as location, contacts, microphone, etc.?**
    A: No. The application strictly follows the "minimum necessary" principle to apply for system permissions, and will not apply for or obtain any system permissions unrelated to the core function of collection recording.

### (4) Troubleshooting
1.  **Q: What should I do if the application crashes?**
    A: You can first try to close the application background process and reopen it; if it still crashes, you can restart your iOS device and try again; please confirm that your device system version is iOS 18.0 and above, and it is a genuine non-jailbroken system; if the above operations cannot solve the problem, you can feedback to us through the contact information at the end of this document.
2.  **Q: What should I do if iCloud sync fails/does not sync?**
    A: Please first confirm that your Apple ID has logged into iCloud normally, and iCloud has sufficient storage space; confirm that iCloud permission has been enabled for Trove in the iOS system settings; check whether the device network status is stable; you can try to turn off the iCloud permission and re-enable it, or restart the device and try again. The iCloud service is independently operated by Apple Inc. If the abnormality continues, you can contact Apple's official customer service for consultation.
3.  **Q: What should I do if the collection pictures cannot be uploaded/loaded?**
    A: Please confirm that you have enabled the photo library/camera permission for the application; confirm that the picture file is not damaged, and the device has sufficient storage space; you can try to close the application background and reopen it, and upload the picture again.

## 4. In-App Purchase Related Instructions
1.  All paid functions, permanent version entitlements, and subscription services of this application are transacted entirely through Apple's official In-App Purchase (IAP) system. All payment processes, order management, automatic renewal, and refund applications are handled by Apple Inc. We only receive the purchase status fed back by Apple's official system, and will not obtain or store any of your payment information, bank card information, or order details.
2.  The paid entitlements you purchase through Apple's IAP system can only be used on the device you are currently using and the corresponding bound Apple ID account, and shall not be transferred, rented, lent, shared or sold to any third party.
3.  The subscription service will be automatically renewed by the Apple system according to the cycle you select, unless you manually turn off the automatic renewal function in the Apple ID account settings in advance. We cannot handle refunds for automatic deductions caused by your failure to cancel the renewal in a timely manner.
4.  All refund applications related to in-app purchases must be submitted through Apple's official channels. We do not directly handle any refund matters, nor can we interfere with the review results of Apple's official refund.

## 5. Advanced Troubleshooting Guide
If you encounter abnormal use of the application, you can troubleshoot step by step according to the following steps, and most problems can be solved through the following operations:
1.  **Basic Restart**: Close the application background process, wait 10 seconds, then reopen the application to check if the abnormality is resolved.
2.  **Device Restart**: Restart your iPhone/iPad device, reopen the application after the restart is complete, to troubleshoot abnormalities caused by temporary system cache.
3.  **System & Version Check**: Confirm that your iOS system version meets the application operation requirements, and the application has been updated to the latest version released on the App Store.
4.  **Permission & Storage Check**: Confirm that the required relevant permissions have been enabled for the application in the iOS system settings, and the device has sufficient storage space.
5.  **iCloud Sync Abnormality Troubleshooting**: Confirm that the Apple ID login status is normal, the iCloud storage space is sufficient, you can try to re-enable the iCloud permission of the application to trigger the system to re-sync.
6.  **Reinstall Application**: If the above operations cannot solve the problem, please make sure that iCloud sync is enabled and the data has been fully synced to the cloud before reinstalling. Then uninstall the application, reinstall it from the App Store, log in to the same Apple ID and enable iCloud permission to restore the data. If iCloud sync is not enabled, uninstalling the application will permanently delete all local data and cannot be recovered.

## 6. User Feedback Guide
If you encounter problems that cannot be solved through the above content, or have function optimization suggestions and bug feedback, you can contact us via email, and we will reply to you within a reasonable period.
- **Contact Email**: rinkakumada@foxmail.com
- **Feedback Suggestion Format**:
  1.  Your device model (e.g.: iPhone 15 Pro)
  2.  iOS system version (e.g.: iOS 18.0)
  3.  Application version number
  4.  Detailed description of the problem and reproduction steps
  5.  Screenshots/screen recordings of related problems (optional)

## 7. Privacy & Compliance Statement
This application strictly complies with the world's mainstream privacy regulations and Apple App Store review rules, abides by the core privacy principles of "zero data collection, full local operation, absolute user control", does not integrate any third-party SDKs, advertising plug-ins, or statistical analysis tools, and all data is independently managed by the user.
- Privacy Policy (English): https://github.com/98Ahua/Trove/blob/main/privacy-policy-en.md
- User Agreement (English): https://github.com/98Ahua/Trove/blob/main/User-Agreement-en.md

## 8. Document Update Statement
This document will be revised synchronously according to the application function iteration, update of laws and regulations, and adjustment of regulatory requirements. The latest version will be updated through in-app announcements and official channels.
- Last Updated: April 2026
