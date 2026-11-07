# 软件游戏合集 Android 项目

这是网站 `https://cn.anotepad.com/notes/hfnpxnda` 的 Android WebView 封装项目。

## 最简单方式：GitHub 云端编译 APK（无需在电脑安装 Android SDK）

1. 在 GitHub 创建一个空仓库（Repository），例如 `software-games-app`。
2. 解压本 ZIP，将里面的所有文件和文件夹（包括隐藏的 `.github` 文件夹）上传到仓库根目录。
3. 打开仓库的 **Actions** 页面，选择 **Build Android APK** 工作流。
4. 点击 **Run workflow**，再点击绿色的 **Run workflow** 确认。
5. 等待工作流变成绿色成功状态，打开该次运行页面最下方的 **Artifacts**。
6. 下载 `软件游戏合集-debug-apk`，解压后得到 `app-debug.apk`。
7. 将 APK 传到安卓手机并安装。首次安装时按系统提示允许浏览器或文件管理器安装未知来源应用。

## Windows 11 本地编译（可选）

1. 安装 Android Studio 稳定版。
2. 打开本项目文件夹，等待 Android Studio 完成 Gradle 同步。
3. 若 Android Studio 提示缺少 SDK，按提示安装 Android SDK Platform 35。
4. 选择 **Build > Build Bundle(s) / APK(s) > Build APK(s)**。
5. APK 输出位置：`app/build/outputs/apk/debug/app-debug.apk`。

## 应用信息

- APP 名称：软件游戏合集
- Application ID：`com.shuai.softwaregames`
- 版本：1.0
- 最低 Android：Android 6.0（API 23）
- 首页：`https://cn.anotepad.com/notes/hfnpxnda`

## 注意

- 这是联网网页封装，不是离线保存的网站内容。
- 网站页面、链接和站点功能仍由 aNotepad 提供。
- GitHub 云端编译会产生 debug APK，适合个人安装测试；若要公开发布，建议后续生成正式签名的 release APK。
