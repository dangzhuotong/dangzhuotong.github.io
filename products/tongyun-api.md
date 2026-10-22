# 橦云接口

**一句话：** 在桌面上调试 API。接口写成仓库里的纯文本，用 Git 管理，不绑云端账号。

**为谁：** 希望用例留在自己的项目仓库里，并能用分支和 Pull Request 看改动的人。

**能干什么：**
- **两种文本：** 可读 IntelliJ 的 .http / .rest，也读 tongyun-collections 里一个接口一个文件的 JSON。
- **直接发请求：** 用 Rust 发出去，不走浏览器的跨域限制。请求头、认证和正文都可以改。
- **多个标签：** 同时改几条请求。可以断言状态码、耗时、JSON 路径和响应头。
- **抽出变量：** 从响应里取出字段，写进当前环境，方便登录之后接着调下一个接口。
- **导入和示例：** 能导入 cURL、Postman Collection v2.1、OpenAPI 3.0 和 .http。可以生成 cURL、JavaScript、TypeScript、Python、Go、Rust 示例。私有变量放在被 Git 忽略的文件里。

**技术栈：** Tauri 2、Rust、React 19、TypeScript、Tailwind CSS

**仓库：** https://github.com/dangzhuotong/tongyun-api

**安装 / Release：** [Releases · 最新版](https://github.com/dangzhuotong/tongyun-api/releases/latest)。当前公开版本是 v0.2.1，有 Windows、macOS Universal 和 Linux 安装包。没有 Apple 公证。0.1.0 没有应用内更新，需要先手动装上 0.2.0 之后的版本。

**状态：** 可用

<!-- screenshots pending: 阿装截图到位后嵌入 ../assets/api-*.png（见同名 .html 注释约定） -->
