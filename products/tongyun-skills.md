# 技能

**一句话：** Skill 素材库。格式遵循 [Agent Skills](https://agentskills.io/specification)，供本机 Cursor、Codex、Claude 与工人机自用；仓库私有，不对外 npm 安装。

**为谁：** 本机已装 skill，在 Cursor、Codex、Claude 与工人机里自用的人。

**能干什么：**
- **tong-chart：** 本地 Mermaid 出图（流程 / 架构 / 时序 / 甘特等），多主题，macOS · Windows · Linux。
- **tong-cover：** 本地 Pillow 封面 / 刊头 / 简报 / 金句卡，按星期换色。
- **tong-git：** 项目仓状态 → 按需提交 → 推到 Gitee / GitHub / CNB。
- **tong-humanize：** 去 AI 味改写：扫描套话 / 三毒 / 标点，按栏目交稿。
- **tong-mysql-ro：** 只读 MySQL：SELECT / SHOW / DESCRIBE，强制 LIMIT，凭证本地填。
- **tong-mysql-write：** 写库 DML：默认预览，确认后 `--apply` 并落回滚 SQL；不做 DDL。
- **仓库里怎么放：** `skills/` 每个 skill 一个目录。`templates/` 是新建 skill 的脚手架，不是 skill。`scripts/` 做校验、打包和脚手架。`docs/` 写怎么写、怎么打包。`playground/` 是本机网页，用来试 skill，不装到系统。

**技术栈：** 仓库里的校验、打包和试跑是 Python 脚本。

**仓库：** https://github.com/dangzhuotong/tongyun-skills

**安装 / Release：** 仓库现为私有，自用。README 没有写 Release。仓库私有，不对外 npm 安装，不承诺公开安装源。

**许可：** MIT

**状态：** 可用

新 skill 按 [AGENTS.md](https://github.com/dangzhuotong/tongyun-skills/blob/master/AGENTS.md) 加，不要往这个仓库塞无关内容。细节看 AGENTS.md 和 [docs/authoring.md](https://github.com/dangzhuotong/tongyun-skills/blob/master/docs/authoring.md)。

`test_skills.py` 会校验 `SKILL.md` 并跑每个 skill 的 `tests/`。不用先装到 `~/.cursor/skills`。`tong-cover` 的测试需要 Pillow：`pip install pillow`。本机网页只绑 `127.0.0.1`，默认打开 http://127.0.0.1:8765 。
