# 影视App下载 · d.818.pw

> 一个开源、轻量、单页面的影视 App 下载导航站点，专注于收集热门影视 App 的 Android 安卓版 APK 下载地址与官方网站入口。

<div align="center">

![License](https://img.shields.io/badge/License-MIT-blue.svg)
![HTML](https://img.shields.io/badge/Build-HTML%2FCSS-orange.svg)
![Version](https://img.shields.io/badge/Version-1.0.0-brightgreen.svg)
[![Website](https://img.shields.io/badge/Website-d.818.pw-red.svg)](https://d.818.pw)

</div>

---

## 📌 项目简介

**影视App下载** 是一个用纯 HTML / CSS 构建的轻量级单页面下载导航站。它把当下热门的影视 App（追剧、看电影、看综艺）的 Android APK 安装包下载地址、官方网站入口集中到同一个页面里，方便用户快速查找、跳转和下载。

整个站点**没有框架、没有构建工具、没有任何运行时依赖**，只有一个 `index.html` 文件。你只需要把它部署到任意静态托管平台上即可上线，非常适合作为开源导航类项目进行二次开发与复用。

---

## 🚀 在线访问

🌐 官方网站：**[https://d.818.pw](https://d.818.pw)**

---

## ✨ 功能特性

- 🎬 **收录热门影视 App**：聚焦影视类应用的安卓版 APK 下载入口。
- 📦 **一键直达下载**：每个应用卡片都提供「APK 下载」和「官网」两个快捷按钮。
- 🎨 **简洁美观的界面**：响应式布局，桌面端双列网格、移动端单列显示，开箱即用。
- 📱 **移动端优先**：适配手机、平板等移动设备，方便在手机上直接下载安装。
- 🔍 **SEO 友好**：内置 title、description、keywords、Open Graph 等 Meta 标签，方便被搜索引擎收录。
- 🧩 **纯静态、零依赖**：一个 HTML 文件搞定，部署简单，随心定制。
- 📊 **集成统计**：内置 Google Analytics（gtag.js），可选使用，按需修改或移除。

---

## 📱 收录影视 App

站点目前收录了以下热门影视应用，点击对应卡片即可跳转到官方下载地址或官网：

| 应用名称 | 说明 |
| :--- | :--- |
| **荐片影视** | 提供电影、电视剧等影视内容，页面提供 Android APK 下载及官网入口。 |
| **网飞猫** | 热门影视应用，提供 Android APK 下载地址及官方网站信息。 |
| **可可影视** | 支持影视内容观看，提供安装包下载地址，方便快速获取。 |
| **好好看 App** | 影视应用，提供 Android APK 下载地址及官方网站入口。 |
| **剧下饭** | 影视应用，通过下载按钮即可获取对应的 Android APK 安装包。 |
| **电影侠** | 影视应用，提供 Android APK 安装包，可通过夸克网盘、百度网盘快速下载。 |

> 新增影视 App 时，只需在 `index.html` 的 `.app-grid` 区域照猫画虎加一个 `<article class="app-card">` 卡片即可，无需改动其他代码。

---

## 🔧 快速开始

### 1. 本地预览

这是一个纯静态页面，直接用浏览器打开即可预览：

```bash
# 直接双击打开 index.html，或使用任意静态服务器
python -m http.server 8000
```

然后访问 `http://localhost:8000` 即可看到效果。

### 2. 部署上线

任选一种静态托管平台，把这个目录一键部署即可：

- **Vercel / Netlify**：直接拖拽导入本仓库，零配置发布。
- **GitHub Pages**：将仓库推送到 GitHub，开启 Pages 并指向根目录。
- **任意服务器 / CDN**：把 `index.html` 上传到服务器或对象存储，绑定你的域名 `d.818.pw` 即可。

### 3. 自定义

- **修改收录的影视 App**：编辑 `index.html` 中的 `.app-card` 结构，替换应用名称、图标文字、下载地址（`href`）与官网地址。
- **修改站点信息**：替换 `<head>` 中的 `title`、`description`、`keywords` 以及 canonical / og 标签的地址。
- **关闭统计**：删除页面底部的 Google Analytics 相关 `<script>` 即可。

---

## 📂 项目结构

```
d.818.pw/
└── index.html        # 单页面站点，包含全部结构、样式与内容
```

---

## 📄 License

本项目基于 **MIT License** 开源，欢迎自由使用、修改与分发。

---

## ⚠️ 免责声明

> APK 文件均来自第三方下载地址，本站仅做信息整理与导航跳转，不存储、不托管任何应用安装包。
>
> - 安装 Android 应用前，请务必确认下载来源可信，并根据设备安全设置进行安装。
> - 应用版本与下载地址可能随时变化，以官方为准。
> - 请遵守当地法律法规，尊重内容版权。

---

## 👨‍💻 我的其他网站

除了影视App下载，我还开发/维护并开源了以下一系列实用工具站，欢迎访问：

- 🗜️ **[7-zip download](https://7zip.world)** — 7-Zip 压缩工具下载
- 🗂️ **[Bandizip](https://bandizip.world)** — Bandizip 压缩软件
- ⬇️ **[DownloadAll](https://downloadall.app)** — 通用下载导航
- 🎨 **[Favicon Generator](https://favicon.pub)** — 网站图标生成器
- 📸 **[ShareX](https://sharex.best)** — ShareX 截图录屏工具
- 🎥 **[VLC Media Player](https://vlcmediaplayer.online)** — VLC 播放器
- 🔍 **[WizTree](https://wiztree.world)** — WizTree 磁盘空间分析
- 🖼️ **[Void Image Viewer](https://voidimageviewer.com/)** — 图片查看器
- 🚀 **[Everything 下载](https://everything.96906.com/)** — Everything 文件搜索工具
- 🌐 **[Video Download Helper](https://videodownloadhelper.world/)** — 视频下载助手
- ⚡ **[FastCopy](https://fastcopy.96906.com/)** — FastCopy 高速文件复制工具

---

<div align="center">

⭐ 如果这个项目对你有帮助，欢迎给我一个 Star，也欢迎提交 Issue 或 PR！

**影视App下载 · [d.818.pw](https://d.818.pw)**

</div>
