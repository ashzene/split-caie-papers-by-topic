# Split CAIE Papers by Topic

[English](#english) · [简体中文](#简体中文)

## English

Build topic-based practice PDFs from Cambridge International past papers. This Agent Skill pairs original question papers (QP) with official mark schemes (MS), then selects questions by what each part assesses.

- Start with local files and check for missing papers by year, series and variant. If browsing is allowed, look for released papers that are missing locally.
- Export a QP and an MS per topic. If a topic spans distinct formats and the paper is unclear, ask which paper to include. Theory and practical formats get separate pairs by default.
- Preserve the context and prerequisites needed to answer each question. Keep matching numbers in the two PDFs, with the newest exam years first and a two-line serif cover.

### Install and try

The skill uses the Agent Skills format. Install the complete folder as `cambridge-topical-papers` in a compatible client's skills directory so it can read `SKILL.md` and `references/`. The optional `agents/openai.yaml` file provides Codex display metadata. [Agent Skills specification](https://agentskills.io/specification)

**Codex** · Invoke with `$cambridge-topical-papers`. [Codex skills documentation](https://learn.chatgpt.com/docs/build-skills)

```sh
git clone https://github.com/ashzene/split-caie-papers-by-topic.git ~/.agents/skills/cambridge-topical-papers
```

**Claude Code** · Invoke with `/cambridge-topical-papers`. [Claude Code skills documentation](https://code.claude.com/docs/en/skills)

```sh
git clone https://github.com/ashzene/split-caie-papers-by-topic.git ~/.claude/skills/cambridge-topical-papers
```

> Build 9618 Topic 19 for Paper 3. Use only local papers from 2025 and save separate QP and MS PDFs in the workspace.

The agent needs access to the source files and tools to read, crop and export PDFs. If it runs remotely, provide the source files or a folder it can access. Finding missing papers online requires network access. [English workflow](references/workflow-en.md)

## 简体中文

把 Cambridge International 历年真题按专题整理成练习册。这个 Agent Skill 会配对原卷题目（QP）和官方评分标准（MS），再按每个小问实际考的内容筛题。

- 优先找本地资料，按年份、场次和卷别查缺。允许联网时，再找已经发布的缺卷。
- 每个专题分别出一份 QP 和 MS。同一专题跨理论和实操等不同考核形式且卷别不明确时，先确认要哪张卷。不同形式默认分册。
- 保留独立作答所需的题干、图表和前置小问。两册题号对应，最新年份在前，每份都用两行衬线封面。

### 安装和试用

技能采用 Agent Skills 格式。安装时把完整文件夹放到工具的技能目录里，文件夹命名为 `cambridge-topical-papers`，让工具能读取 `SKILL.md` 和 `references/`。可选的 `agents/openai.yaml` 用于配置 Codex 里的显示信息。 [Agent Skills 规范](https://agentskills.io/specification)

**Codex** · 用 `$cambridge-topical-papers` 调用。 [Codex 技能文档](https://learn.chatgpt.com/docs/build-skills)

```sh
git clone https://github.com/ashzene/split-caie-papers-by-topic.git ~/.agents/skills/cambridge-topical-papers
```

**Claude Code** · 用 `/cambridge-topical-papers` 调用。 [Claude Code 技能文档](https://code.claude.com/docs/en/skills)

```sh
git clone https://github.com/ashzene/split-caie-papers-by-topic.git ~/.claude/skills/cambridge-topical-papers
```

> 整理 9618 Topic 19 的 Paper 3。只用本地 2025 年原卷，把 QP 和 MS 分别放到工作区。

运行时需要能访问原卷，并且能读取、裁剪和导出 PDF。用云端工具时，可以上传原卷或指定它能访问的文件夹。联网查缺卷需要网络权限。 [中文工作流](references/workflow-zh-CN.md)

## Contributors / 贡献者

- [ashzene](https://github.com/ashzene) — workflow requirements and end-to-end testing / 流程需求与实际试用
- [OpenAI Codex](https://github.com/codex) — skill workflow and bilingual documentation / 技能工作流与双语文档

## License / 许可证

The [MIT License](LICENSE) covers the skill and its documentation. Cambridge exam materials remain subject to their own terms.

技能及说明采用 [MIT 许可证](LICENSE)。Cambridge 原卷和评分标准仍以各自的使用条款为准。
