# 本地开发机

**一句话：** 把这台电脑上的开发项目登记到一处：一键启停、看状态、跟日志。人看窗口，AI 读 JSON。

**为谁：** 本机经常同时跑好几个服务的人，以及希望助手能读到项目状态和日志、自己再接手的人。

**能干什么：**
- **扫描目录：** 自动认出 Spring Boot、Tomcat WAR、Vite、Vue CLI、Next、Nuxt、Python 等，并建议端口和启动命令。
- **三个入口：** 桌面窗口、本机网页（默认 127.0.0.1:9099）和命令行，共用同一个 Rust 核心。
- **分组启动：** 按依赖顺序启停、重启，日志跟在旁边。
- **给 AI 的状态：** 命令行可以输出 JSON：是否在跑、端口、日志路径、失败原因。
- **清单留在本机：** 项目列表写在 ~/.config/tongyun-dev/projects.toml，不进仓库。

**技术栈：** Rust、Tauri 2、React。命令行需要 Rust 1.85 及以上；桌面壳需要 Node.js 20 及以上，以及 Rust 1.88 及以上。

**仓库：** https://github.com/dangzhuotong/tongyun-dev

**安装 / Release：** [Releases · 最新版](https://github.com/dangzhuotong/tongyun-dev/releases/latest)。当前公开版本是 v0.2.1，有 Windows、macOS Universal 和 Linux 安装包。安装包没有 Apple 公证。进程停止和状态查询目前只支持 Unix（用到 kill、ps、lsof、tail）。

**许可：** MIT

**状态：** 可用
