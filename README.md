# QPALZM Toolkit

> **简体中文** | **English** — Dual-language documentation

---

[中文文档](#中文文档) | [English Documentation](#english-documentation)

---

<a id="中文文档"></a>

由 AdkSetup 开发的轻量实用工具集，专注解决日常开发与系统操作中的小问题，全部项目均已发布稳定版本。

## 项目列表

| 项目名称 | 简介 | 支持平台 | 状态 |
|---|---|---|---|
| [Real-Full-Installer](https://github.com/adksetup/Real-Full-Installer) | 完整安装包制作与静默安装工具，自动适配 brew / apt 包管理器（已发布 v0.2） | macOS / Linux | 已发布 |
| [Pip-GUI](https://github.com/adksetup/Pip-GUI) | 图形化 Pip 包管理工具，可视化执行安装 / 卸载 / 检索（已发布 v0.1） | Windows / macOS / Linux | 已发布 |
| [QPALZM-Web-Search](https://github.com/adksetup/QPALZM-Web-Search) | macOS/Windows 网页搜索 GUI 工具，支持百度、必应检索与自定义网址打开（已发布 v0.3） | macOS / Windows | 已发布 |
| [Brew-GUI](https://github.com/adksetup/Brew-GUI) | macOS / Linux 图形化 Homebrew 管理工具，无需敲终端命令（已发布 v0.1） | macOS / Linux | 已发布 |

## 设计理念

- **极简高效**：只做核心功能，拒绝臃肿复杂的界面，用最简单的方式解决实际问题
- **开箱即用**：所有项目均提供二进制包，无需复杂配置，下载即可运行
- **持续迭代**：根据实际使用场景不断优化功能，修复问题，保持长期维护

## 使用说明

1. **获取工具**：点击项目列表中的链接，进入对应仓库
2. **下载版本**：在仓库的「Releases」页面，选择对应平台的最新版本二进制包下载
3. **查看文档**：每个项目的 README.md 中都有详细的使用说明和依赖信息

## 注意事项

- **Real-Full-Installer** 与 **Brew-GUI** 需系统已预先安装 Homebrew（macOS）或包管理器（Linux）
- **QPALZM-Web-Search** 使用 macOS 原生 `open` 命令唤起浏览器，仅适配苹果系统
- **Pip-GUI** 在 Windows 下建议以管理员权限运行，以确保文件读写等操作正常
- 部分工具在安装 / 卸载软件时可能需要终端密码授权
- 所有工具均为个人开发，若遇到问题可在对应仓库提交 Issue

## 关于作者

**AdkSetup** — 专注于开发实用、轻量的小工具，解决日常开发与系统使用中的各种小痛点。

---

<a id="english-documentation"></a>

A lightweight collection of practical utilities by AdkSetup, focused on solving small but annoying problems in everyday development and system operations. All projects have reached stable releases.

## Project List

| Project | Description | Platforms | Status |
|---|---|---|---|
| [Real-Full-Installer](https://github.com/adksetup/Real-Full-Installer) | Complete installer builder and silent installation tool, auto-adapts to brew / apt package managers (v0.2 released) | macOS / Linux | Released |
| [Pip-GUI](https://github.com/adksetup/Pip-GUI) | Graphical Pip package manager for visual install / uninstall / search (v0.1 released) | Windows / macOS / Linux | Released |
| [QPALZM-Web-Search](https://github.com/adksetup/QPALZM-Web-Search) | macOS-only web search GUI tool with Baidu, Bing search and custom URL opening (v0.1 released) | macOS | Released |
| [Brew-GUI](https://github.com/adksetup/Brew-GUI) | Graphical Homebrew manager for macOS and Linux — no terminal required (v0.1 released) | macOS / Linux | Released |

## Design Philosophy

- **Minimal and efficient**: core features only, no bloated interfaces, solving real problems the simplest way possible
- **Ready out of the box**: every project ships as a binary package — download and run, no complex setup
- **Continuous iteration**: features are refined and bugs are fixed based on real usage, with long-term maintenance

## Usage

1. **Get the tool**: click a project link in the table above to visit its repository
2. **Download a release**: go to the repository's **Releases** page and download the latest binary for your platform
3. **Read the docs**: each project's `README.md` contains detailed usage instructions and dependency information

## Notes

- **Real-Full-Installer** and **Brew-GUI** require Homebrew (macOS) or a system package manager (Linux) to be installed beforehand
- **QPALZM-Web-Search** uses the native macOS `open` command to launch the browser, so it only works on Apple systems
- **Pip-GUI** is recommended to run with administrator privileges on Windows to ensure normal file read/write operations
- Some tools may require terminal password authorization when installing or uninstalling software
- These are personal projects — if you run into a problem, please open an issue in the corresponding repository

## About the Author

**AdkSetup** — focused on building practical, lightweight tools that solve the small everyday pains of development and system use.

---

## License

This project is licensed under the [MIT License](./LICENSE).
