# Split CAIE Papers by Topic

[简体中文](README.zh-CN.md)

Build topic-based practice PDFs from Cambridge International past papers. This Agent Skill pairs original question papers (QP) with official mark schemes (MS), then selects questions by what each part assesses.

- Start with local files and check for missing papers by year, series and variant. If browsing is allowed, look for released papers that are missing locally.
- Export a QP and an MS per topic. If a topic spans distinct formats and the paper is unclear, ask which paper to include. Theory and practical formats get separate pairs by default.
- Preserve the context and prerequisites needed to answer each question. Keep matching numbers in the two PDFs, with the newest exam years first and a two-line serif cover.

## Install globally

Requires Git and Node.js 22.20 or later. Run the command and select your AI client. If Windows PowerShell blocks `npx`, use `npx.cmd`.

```sh
npx skills add ashzene/split-caie-papers-by-topic --global --skill cambridge-topical-papers --copy
```

[Supported clients](https://github.com/vercel-labs/skills/blob/main/docs/agents.md)

## Try it

Open your client and start a new session. Use `$cambridge-topical-papers` in Codex, `/cambridge-topical-papers` in Claude Code, or select the skill by name in your client's skill menu. [Codex skills documentation](https://learn.chatgpt.com/docs/build-skills) · [Claude Code skills documentation](https://code.claude.com/docs/en/skills)

> Build 9618 Topic 19 for Paper 3. Use only local papers from 2025 and save separate QP and MS PDFs in the workspace.

The agent needs access to the source files and tools to read, crop and export PDFs. If it runs remotely, provide the source files or a folder it can access. Finding missing papers online requires network access. [English workflow](references/workflow-en.md)

## License

The [MIT License](LICENSE) covers the skill and its documentation. Cambridge exam materials remain subject to their own terms.
