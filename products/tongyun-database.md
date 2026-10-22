# 橦云数据库

**一句话：** 人和 AI 共用的本机数据库工作台。改一行之前，先看见将要执行的 SQL，以及怎么退回去。

**为谁：** 要在自己电脑上查库、改一条记录并留下痕迹的人。也给通过本机接口操作同一份计划的助手。

**能干什么：**
- **先连再查：** 支持 SQLite 沙箱、MySQL 和 Redis 7 及以上。第一次打开只建一个合成的 SQLite，别的连接自己加。
- **看表：** 按主键翻页，结果只画看得见的行。任意 SQL 的结果只读。
- **改一行：** 单行修改会先给出正向 SQL 和回滚 SQL，确认之后才执行。数据和结构若对不上，会拒绝。
- **时间线：** 开始、成功、失败、确认和取消都记在本机，需要时再核对并回滚。
- **同一套接口：** 网页和本机 HTTP API 用的是同一个库。可选 MCP，默认只注册只读工具。命令行目前只适配 SQLite。

**技术栈：** Node.js 24 及以上、JavaScript。PostgreSQL、Cloudflare D1 和内置大模型聊天还没有。Drizzle 只是后续候选，不是现在的功能。

**仓库：** https://github.com/dangzhuotong/tongyun-database

**安装 / Release：** [Releases · v0.1.1](https://github.com/dangzhuotong/tongyun-database/releases/latest)。v0.1.1 提供 macOS 压缩包 tongyun-database-mac.zip。解压后把「橦云数据库.app」放进应用程序文件夹，启动后用浏览器打开本机工作台（http://127.0.0.1:4319）。本机需要已经装好 Node.js 24 或以上。还没有 Windows 和 Linux 安装包。首次打开因为没有公证，需要右键选择「打开」。

**许可：** MIT

**状态：** 打磨中

<!-- screenshots pending: 阿装截图到位后嵌入 ../assets/database-*.png（见同名 .html 注释约定） -->
