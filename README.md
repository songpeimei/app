# DeepSeek Chat

基于DeepSeek API的Android聊天应用。

[![Build APK](https://github.com/YOUR_USERNAME/YOUR_REPO/actions/workflows/build-apk.yml/badge.svg)](https://github.com/YOUR_USERNAME/YOUR_REPO/actions/workflows/build-apk.yml)

## 自动构建APK

本项目使用GitHub Actions自动构建APK，无需本地安装Android SDK。

### 使用方法

1. **Fork或上传此项目到GitHub**
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO.git
   git push -u origin main
   ```

2. **触发构建**
   - 推送代码后自动触发
   - 或在GitHub仓库页面 → Actions → Build Android APK → Run workflow

3. **下载APK**
   - 构建完成后，在 Actions 页面下载 artifacts
   - 包含 `app-debug` 和 `app-release` 两个APK

## 功能特性

- ✅ 与DeepSeek AI对话
- ✅ 支持自定义API Key
- ✅ Material Design界面
- ✅ 异步网络请求

## 本地构建

如需本地构建，请安装Android Studio或Android SDK后运行：
```bash
./gradlew assembleDebug
```

## 技术栈

- Kotlin
- Android SDK 34
- OkHttp (网络请求)
- Gson (JSON解析)
- Kotlin Coroutines (异步)
