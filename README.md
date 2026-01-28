# Excalidraw 桌面版

一个基于 [Excalidraw](https://excalidraw.com) 的轻量级、隐私友好的桌面应用，使用 [Tauri](https://tauri.app) 构建 —— 支持 **macOS**、**Linux** 和 **Windows**。

完全离线运行 Excalidraw 作为本地桌面应用，非常适合制作图表、快速草图和创意构思 —— 无需浏览器即可使用。

---

## ⚡ 功能特性

- ✅ **离线优先** — 无需互联网连接
- ✅ **跨平台** — 支持 Mac、Linux 和 Windows
- ✅ **轻量级** — 基于 Tauri 构建（比 Electron 小很多）
- ✅ **会话持久化** — 应用重启后您的绘图保持完整

---

## 🚨 重要提示

> ⚠️ **保存的文件存储在系统的下载文件夹中**  
> 当您手动保存或导出绘图时，文件将写入到您操作系统的默认 **下载** 目录。

---

## 📦 安装

从 [发布页面](https://github.com/burnt0rice/excalidraw-desktop/releases) 下载适合您平台的最新版本。

- **macOS** – `.dmg` 安装程序
- **Windows** – `.msi` 或 `.exe` 安装程序
- **Linux** – `.AppImage`、`.deb` 或 `.tar.gz` 包

---

## 📋 中文版本特性

- ✅ **完整中文界面** — 界面完全中文化
- ✅ **便携版支持** — 提供无需安装的便携版
- ✅ **本地数据存储** — 所有数据保存在本地
- ✅ **多格式导出** — 支持 PNG、SVG、JSON 等格式

---

## 🧾 许可证

本项目采用 [MIT 许可证](LICENSE) 开源。

---

## 🙌 致谢

- [Excalidraw](https://github.com/excalidraw/excalidraw)
- 桌面应用基于 [Tauri](https://tauri.app) 构建

---

## 💬 反馈与贡献

欢迎提交问题、功能请求和拉取请求。  
让我们一起让离线绘图变得更美好！ ✨

---

## 🔧 开发说明

### 构建便携版

```bash
# 安装依赖
npm install

# 构建前端
npm run build

# 构建 Tauri 应用（生成安装包）
npm run tauri build
```

### 开发模式

```bash
# 启动开发服务器
npm run dev
```

### 项目结构

- `src/` - React 前端源代码
- `src-tauri/` - Tauri Rust 后端代码
- `portable/` - 便携版打包文件
- `public/` - 静态资源文件

---



