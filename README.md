# MiniCPM-o4.5 Windows 本地运行版 🖥️

<div align="center">

![Platform](https://img.shields.io/badge/Platform-Windows-blue?style=flat-square&logo=windows)
![Installer Size](https://img.shields.io/badge/安装包-仅%2010MB-brightgreen?style=flat-square)
![Model Size](https://img.shields.io/badge/模型大小-约%208GB-orange?style=flat-square)
![CPU Support](https://img.shields.io/badge/推理-CPU%20支持-yellow?style=flat-square)

**无需 GPU · 纯 CPU 推理 · 开箱即用的语音交互体验**

</div>

---

## ✨ 项目简介

本项目是 [MiniCPM-o4.5](https://github.com/OpenBMB/MiniCPM-o) 的 Windows 本地运行版本，提供一个极简安装包，让你在普通 Windows 电脑上即可体验端侧多模态大模型的语音交互能力，无需 GPU，无需复杂环境配置。

---

## 🚀 快速开始

### 1. 下载安装包

前往 [Releases](../../releases) 页面下载最新版本：

```
MiniCPM-o4.5 本地小程序cpu版.msi
```

> 安装包体积仅约 **10 MB**，下载极速。

### 2. 安装程序

双击 `.msi` 文件，按照安装向导完成安装即可。

### 3. 首次启动 · 自动下载模型

首次运行程序时，将自动从网络下载模型文件（约 **8 GB**），请确保：

- 网络连接稳定
- 磁盘剩余空间 ≥ 10 GB
- 耐心等待下载完成（视网速而定）

下载完成后，后续启动无需重复下载。

---

## 💻 系统要求

| 项目 | 要求 |
|------|------|
| 操作系统 | Windows 10 / Windows 11（64位） |
| 处理器 | x86-64 架构，支持纯 CPU 推理 |
| 内存 | 建议 16 GB RAM 及以上 |
| 磁盘空间 | 安装包 ~10 MB + 模型文件 ~8 GB |
| 网络 | 首次启动需联网下载模型 |

> ⚠️ 暂不支持 GPU 加速，当前版本为纯 CPU 推理模式。

---

## 🎙️ 功能特性

- **语音交互**：支持实时语音输入与语音输出，自然对话体验
- **纯 CPU 推理**：无需独立显卡，普通办公电脑即可运行
- **本地隐私**：模型完全在本地运行，数据不上传云端
- **轻量安装**：安装包仅 10 MB，模型按需自动下载

---

## ❓ 常见问题

**Q: 模型下载失败怎么办？**  
A: 请检查网络连接，或尝试使用代理。重新启动程序会继续断点下载。

**Q: 运行速度很慢正常吗？**  
A: CPU 推理相比 GPU 速度较慢，属于正常现象。建议在性能较强的 CPU 上运行以获得更好体验。

**Q: 支持哪些语言？**  
A: MiniCPM-o4.5 支持中英文交互，以中文效果最佳。

---

## 📄 相关链接

- [MiniCPM-o 官方仓库](https://github.com/OpenBMB/MiniCPM-o)
- [MiniCPM-o4.5 模型介绍](https://huggingface.co/openbmb/MiniCPM-o-2_6)

---

## 📜 License

本项目遵循上游 MiniCPM-o 项目的开源协议，请参阅官方仓库获取详细信息。
