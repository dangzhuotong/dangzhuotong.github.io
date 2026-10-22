# 桌面 Git

**一句话：** 独立的桌面 Git 客户端，用法靠近 IntelliJ IDEA 自带的 Git 面板，提交说明可以请模型起一稿。

**为谁：** 想在编辑器外面看改动、暂存、提交和推拉的人。

**能干什么：**
- **打开仓库：** 输入路径、用系统对话框选目录，或把文件夹拖进窗口。还不是仓库的目录可以一键 git init。
- **对照改动：** 工作区和暂存区分开看。可以按文件、按代码块，或按行暂存。丢弃前会再确认，并留一小段可撤销的快照。
- **提交：** 支持修正上一次提交。可以用 KIE、OpenAI 兼容接口或本机 Ollama 生成 Conventional Commits 说明。密钥存成本地加密文件。
- **分支和历史：** 切换、新建分支，看提交树。
- **推拉：** Fetch、Pull、Push。操作日志记下命令和输出，并打码地址里的凭据。

**技术栈：** Tauri 2、Rust（git2 与系统自带的 git）、React 19、TypeScript、Vite、Tailwind CSS 4

**仓库：** https://github.com/dangzhuotong/tongyun-git

**安装 / Release：** [Releases · 最新版](https://github.com/dangzhuotong/tongyun-git/releases/latest)。当前公开版本是 v0.1.1，有 Windows、macOS Universal 和 Linux 安装包。没有 Apple 签名和公证。仓库说明写明：MVP 核心阶段（M0 到 M6）已经实现。

**状态：** 可用
