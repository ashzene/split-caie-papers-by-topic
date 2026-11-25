# Split CAIE Papers by Topic

[English](#english) · [简体中文](#简体中文)

## English

Build topic-based practice PDFs from Cambridge International past papers. This Agent Skill pairs original question papers (QP) with official mark schemes (MS), then selects questions by what each part assesses.

- Start with local files and check for missing papers by year, series and variant. If browsing is allowed, look for released papers that are missing locally.
- Export a QP and an MS per topic. If a topic spans distinct formats and the paper is unclear, ask which paper to include. Theory and practical formats get separate pairs by default.
- Preserve the context and prerequisites needed to answer each question. Keep matching numbers in the two PDFs, with the newest exam years first and a two-line serif cover.

### Install from a terminal

With Git and Node.js 22.20 or later installed, run the command for your system and choose your AI client when prompted. [Skills CLI documentation](https://github.com/vercel-labs/skills/blob/main/docs/commands.md)

**macOS and Linux** · Terminal

```bash
npx skills add ashzene/split-caie-papers-by-topic --global --skill cambridge-topical-papers --copy
```

**Windows** · PowerShell or Command Prompt

```powershell
npx.cmd skills add ashzene/split-caie-papers-by-topic --global --skill cambridge-topical-papers --copy
```

To select a client directly, add `--agent` and its ID to the same command. This example targets Cursor on macOS and Linux.

```bash
npx skills add ashzene/split-caie-papers-by-topic --global --skill cambridge-topical-papers --copy --agent cursor
```

| AI client | `--agent` value |
| --- | --- |
| Codex | `codex` |
| Claude Code | `claude-code` |
| Cursor | `cursor` |
| GitHub Copilot | `github-copilot` |
| OpenCode | `opencode` |
| Gemini CLI | `gemini-cli` |
| Windsurf | `windsurf` |

`--global` installs for your user account across projects. To install for one project, run the command from its root and omit `--global`. [Full list of clients and install paths](https://github.com/vercel-labs/skills/blob/main/docs/agents.md)

For manual installation, clone or copy the full repository into your client's skills directory as `cambridge-topical-papers`. Keep `SKILL.md` and `references/` together. The optional `agents/openai.yaml` file provides Codex display metadata. [Agent Skills specification](https://agentskills.io/specification)

### Try it

Open your client and start a new session. Use `$cambridge-topical-papers` in Codex, `/cambridge-topical-papers` in Claude Code, or select the skill by name in your client's skill menu. [Codex skills documentation](https://learn.chatgpt.com/docs/build-skills) · [Claude Code skills documentation](https://code.claude.com/docs/en/skills)

> Build 9618 Topic 19 for Paper 3. Use only local papers from 2025 and save separate QP and MS PDFs in the workspace.

The agent needs access to the source files and tools to read, crop and export PDFs. If it runs remotely, provide the source files or a folder it can access. Finding missing papers online requires network access. [English workflow](references/workflow-en.md)

## 简体中文

把 Cambridge International 历年真题按专题整理成练习册。这个 Agent Skill 会配对原卷题目（QP）和官方评分标准（MS），再按每个小问实际考的内容筛题。

- 优先找本地资料，按年份、场次和卷别查缺。允许联网时，再找已经发布的缺卷。
- 每个专题分别出一份 QP 和 MS。同一专题跨理论和实操等不同考核形式且卷别不明确时，先确认要哪张卷。不同形式默认分册。
- 保留独立作答所需的题干、图表和前置小问。两册题号对应，最新年份在前，每份都用两行衬线封面。

### 从终端安装

装好 Git 和 Node.js 22.20 或更新版本后，按系统运行下面的命令，再在安装器里选择你用的 AI 客户端。 [Skills CLI 说明](https://github.com/vercel-labs/skills/blob/main/docs/commands.md)

**macOS 和 Linux** · 终端

```bash
npx skills add ashzene/split-caie-papers-by-topic --global --skill cambridge-topical-papers --copy
```

**Windows** · PowerShell 或命令提示符

```powershell
npx.cmd skills add ashzene/split-caie-papers-by-topic --global --skill cambridge-topical-papers --copy
```

也可以在同一条命令末尾加上 `--agent` 和客户端 ID，直接指定装给谁。下面这条命令适用于 macOS 和 Linux 上的 Cursor。

```bash
npx skills add ashzene/split-caie-papers-by-topic --global --skill cambridge-topical-papers --copy --agent cursor
```

| AI 客户端 | `--agent` 参数值 |
| --- | --- |
| Codex | `codex` |
| Claude Code | `claude-code` |
| Cursor | `cursor` |
| GitHub Copilot | `github-copilot` |
| OpenCode | `opencode` |
| Gemini CLI | `gemini-cli` |
| Windsurf | `windsurf` |

`--global` 会把技能安装给当前用户，各个项目都能用。只想给某个项目安装时，在项目根目录运行命令并去掉 `--global`。 [完整客户端列表和安装路径](https://github.com/vercel-labs/skills/blob/main/docs/agents.md)

手动安装时，把整个仓库克隆或复制到客户端的技能目录，文件夹命名为 `cambridge-topical-papers`，一起保留 `SKILL.md` 和 `references/`。可选的 `agents/openai.yaml` 用于配置 Codex 里的显示信息。 [Agent Skills 规范](https://agentskills.io/specification)

### 试用

装好后打开客户端，新建一个对话。Codex 里用 `$cambridge-topical-papers`，Claude Code 里用 `/cambridge-topical-papers`，其他客户端可以在技能菜单里按名称选择。 [Codex 技能文档](https://learn.chatgpt.com/docs/build-skills) · [Claude Code 技能文档](https://code.claude.com/docs/en/skills)

> 整理 9618 Topic 19 的 Paper 3。只用本地 2025 年原卷，把 QP 和 MS 分别放到工作区。

运行时需要能访问原卷，并且能读取、裁剪和导出 PDF。用云端工具时，可以上传原卷或指定它能访问的文件夹。联网查缺卷需要网络权限。 [中文工作流](references/workflow-zh-CN.md)

## License / 许可证

The [MIT License](LICENSE) covers the skill and its documentation. Cambridge exam materials remain subject to their own terms.

技能及说明采用 [MIT 许可证](LICENSE)。Cambridge 原卷和评分标准仍以各自的使用条款为准。
