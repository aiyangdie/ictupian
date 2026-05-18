<div align="center">

# 🖼️ IC智能图片压缩

**高质量在线图片压缩工具 — 纯前端处理，隐私安全**

[![GitHub](https://img.shields.io/badge/GitHub-Project-blue?logo=github)](https://github.com/aiyangdie/ictupian)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

</div>

---

## 📌 项目简介

IC智能图片压缩是一款纯前端实现的在线图片压缩工具，所有压缩处理均在浏览器本地完成，图片不会上传至任何服务器，充分保障用户隐私。支持批量压缩、实时进度追踪、一键打包下载，压缩率可达 50%-80%，同时保持原始文件名和 EXIF 信息。

---

## ✨ 核心特性

- 🗜️ **智能有损压缩** — 体积减少 50%-80%，视觉质量几乎无损
- 🔒 **纯前端处理** — 图片不上传服务器，隐私零泄露
- 📦 **批量压缩** — 支持多文件同时处理，实时显示总进度
- 📥 **一键打包下载** — 多文件自动打包为 ZIP，单文件直接下载
- 🏷️ **保留原始文件名** — 压缩后文件名不变，方便管理
- 📊 **详细压缩报告** — 显示原始大小、压缩后大小、节省百分比
- 🖼️ **实时缩略图预览** — 压缩结果附带图片预览
- ⚡ **WebWorker 加速** — 压缩任务在独立线程运行，不阻塞 UI
- 📱 **拖拽上传** — 支持拖拽文件到上传区域，操作便捷
- 🎨 **响应式设计** — 完美适配桌面端与移动端

---

## 🛠️ 技术栈

| 技术 | 用途 |
|------|------|
| HTML5 | 页面结构与文件上传 API |
| CSS3 | 样式与响应式布局（Flexbox、渐变进度条） |
| JavaScript (ES6+) | 压缩逻辑、文件处理、异步控制流 |
| [browser-image-compression](https://github.com/Donaldcwl/browser-image-compression) | 核心图片压缩引擎 |
| [JSZip](https://stuk.github.io/jszip/) | 多文件 ZIP 打包下载 |
| Font Awesome 6.0 | 图标系统 |

---

## 🚀 快速开始

### 前置条件

- 现代浏览器（Chrome / Firefox / Safari / Edge）
- 无需安装任何依赖

### 安装步骤

```bash
git clone https://github.com/aiyangdie/ictupian.git
cd ictupian
```

### 运行命令

```bash
# 方式一：直接打开
start index.html

# 方式二：VSCode Live Server（推荐）

# 方式三：Python 简易服务器
python -m http.server 8080
```

### 在线演示

🔗 [IC智能图片压缩](https://ic.aikex.ink)

---

## 📂 项目结构

```
ictupian/
├── index.html                       # 主页面
├── style.css                        # 样式文件（进度条、卡片布局）
├── script.js                        # 压缩逻辑、拖拽上传、ZIP打包
├── favicon.ico                      # 网站图标
├── CNAME                            # 自定义域名配置
├── wechat_2025-04-29_044012_213.png # 演示截图
└── README.md                        # 项目说明文档
```

---

## 🤝 贡献与许可证

欢迎提交 Issue 和 Pull Request 来帮助改进项目！

本项目采用 **MIT License** 开源协议，详情请见 [LICENSE](LICENSE) 文件。
