# Split CAIE Papers by Topic

[English](README.md)

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

## 许可证

技能及说明采用 [MIT 许可证](LICENSE)。Cambridge 原卷和评分标准仍以各自的使用条款为准。
