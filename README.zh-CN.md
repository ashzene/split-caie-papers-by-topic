# Split CAIE Papers by Topic

[English](README.en.md)

把 Cambridge International 历年真题按专题整理成练习册。这个 Agent Skill 会配对原卷题目（QP）和官方评分标准（MS），再按每个小问实际考的内容筛题。

- 优先找本地资料，按年份、场次和卷别查缺。允许联网时，再找已经发布的缺卷。
- 每个专题分别出一份 QP 和 MS。同一专题跨理论和实操等不同考核形式且卷别不明确时，先确认要哪张卷。不同形式默认分册。
- 保留独立作答所需的题干、图表和前置小问。两册题号对应，最新年份在前，每份都用两行衬线封面。

## 全局安装

需要 Git 和 Node.js 22.20 或更新版本。运行命令后选择你的 AI 客户端。Windows PowerShell 如果拦截 `npx`，就把它换成 `npx.cmd`。

```sh
npx skills add ashzene/split-caie-papers-by-topic --global --skill cambridge-topical-papers --copy
```

[支持的客户端](https://github.com/vercel-labs/skills/blob/main/docs/agents.md)

## 试用

装好后打开客户端，新建一个对话。Codex 里用 `$cambridge-topical-papers`，Claude Code 里用 `/cambridge-topical-papers`，其他客户端可以在技能菜单里按名称选择。 [Codex 技能文档](https://learn.chatgpt.com/docs/build-skills) · [Claude Code 技能文档](https://code.claude.com/docs/en/skills)

> 整理 9618 Topic 19 的 Paper 3。只用本地 2025 年原卷，把 QP 和 MS 分别放到工作区。

运行时需要能访问原卷，并且能读取、裁剪和导出 PDF。用云端工具时，可以上传原卷或指定它能访问的文件夹。联网查缺卷需要网络权限。 [中文工作流](references/workflow-zh-CN.md)

## 许可证

技能及说明采用 [MIT 许可证](LICENSE)。Cambridge 原卷和评分标准仍以各自的使用条款为准。
