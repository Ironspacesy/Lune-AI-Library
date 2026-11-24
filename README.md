# Lune's AI Library

**From Imagination to Implementation.**
从想象，到实现。

[English](#english) · [简体中文](#简体中文)

![Version v0.1.0](https://img.shields.io/badge/version-v0.1.0-356b55) [![CC BY 4.0](https://img.shields.io/badge/license-CC%20BY%204.0-356b55)](LICENSE) ![English and Simplified Chinese](https://img.shields.io/badge/languages-EN%20%7C%20ZH--CN-485c72)

## English

### Introduction

Lune's AI Library is a personal archive and an open lab for AI workflows, reusable prompts, agent skills, practical tools, and methods for working with AI. It starts with an interview documentary and a filmmaking workflow drawn from the project. Each entry grows out of a real problem, repeated trials, and human review.

**Don't just collect prompts. Collect ways of creating.**

### Philosophy

- **Human intention, AI execution.** People set the goals, make creative decisions, and judge the outcome. AI helps turn those decisions into work that can be inspected and revised.
- **Understand before implementing.** Read the material, clarify the problem, and establish constraints.
- **Practice before abstraction.** Derive methods from a real project and describe where they were tested.
- **Support creativity with engineering.** Use reproducible processes, version history, and verifiable results to make creative work easier to refine.
- **Prefer iteration over perfection.** Use review and feedback to improve the work over time.
- **Preserve and share the method.** Record what worked, what failed, and what others can reuse.

### Available workflows

| Workflow | What it covers | Version |
|---|---|---|
| [001 · AI-assisted Filmmaking](workflows/ai-filmmaking/README.md#english) | Interview-led editing, visual design, staged review, final mastering, and project archiving | V1.0 |

`workflows/<topic>/` contains an overview, both languages of the master prompt, a revision template, and a change log. See the [library changelog](CHANGELOG.md) for release history.

### How to use

1. Choose a workflow and read its prerequisites and limits.
2. Copy the master prompt in your preferred language and supply your brief, available inputs, and constraints.
3. Set approval points with the agent. Inspect outputs and specify revisions with a baseline version, timecodes where applicable, and acceptance criteria.

### Roadmap

Areas for future exploration include academic learning, scientific research, literature review, computational physics, scientific visualization, software development, personal knowledge management, creative writing and storytelling, deep research, agent skills and automation, and human–AI collaboration methods.

### Contributions and maintenance

For proposed additions, document the real problem, the reusable method, its technical requirements, what was personally verified, likely failure cases, and the version. Mark early experiments explicitly. Include material that is appropriate for public use, with permissions and attribution where needed.

Add an end-to-end method under `workflows/`, a standalone instruction under `prompts/`, a verified agent module under `skills/`, runnable code under `tools/`, or a retrospective under `case-studies/`. Create a directory when its first entry is ready. Update both language indexes and the relevant changelog, then review with `git diff`. Stage the intended files with `git add <paths>`, commit them, and push the branch. For a release, tag the checked commit and publish bilingual notes based on the changelog.

### License

Repository documentation, workflows, and prompts are available under [CC BY 4.0](LICENSE) to the extent Lune can license them. You may copy, adapt, and use them commercially with appropriate credit to Lune, a link to the license, and an indication of changes. Third-party material retains its own terms.

### About

Maintained by **Lune**. Established November 24, 2026.

*Build things. Learn from them. Preserve the methods. Share the possibilities.*

---

## 简体中文

### 项目简介

Lune's AI Library（个人 AI 实践库）是一份个人知识档案，也是一个开放实验室，收录 AI 工作流、可复用提示词、Agent 技能、实用工具和人机协作方法。它从一部人物采访纪录短片和由此整理的影视工作流起步。每份内容都来自一个真实问题，经过试验、迭代与人工判断。

**不只是收集提示词，而是收藏创造的方法。**

### 核心理念

- **人定目标，AI 协作。** 人负责目标、创意和验收，AI 帮助实现可检查、可修改的成果。
- **先理解，再执行。** 先读懂素材、厘清问题，再确定工作条件。
- **从实践中提炼方法。** 以真实项目为起点，交代方法经过了怎样的验证。
- **用工程方法支持创造。** 让流程可以复现，版本可以追踪，结果可以验证。
- **用迭代改进作品。** 通过审阅和反馈持续调整。
- **保存并分享方法。** 记录有效做法、失败情境，以及别人可以复用的经验。

### 已收录工作流

| 工作流 | 内容 | 版本 |
|---|---|---|
| [001 · AI 辅助影视创作](workflows/ai-filmmaking/README.md#简体中文) | 采访剪辑、视觉设计、分阶段审阅、最终母版与工程归档 | V1.0 |

`workflows/<主题>/` 存放工作流说明、中英文 Master Prompt、迭代模板和更新记录。仓库发布记录见[总更新日志](CHANGELOG.md)。

### 使用方法

1. 选择工作流并查看技术条件和适用范围。
2. 复制所需语言的 Master Prompt，填写项目需求、可用输入和限制。
3. 与 Agent 约定需要人工批准的节点。审阅输出时注明基准版本、适用的时间码和验收标准。

### 未来探索

可能涉及学术学习、科学研究、文献综述、计算物理、科学可视化、软件开发、个人知识管理、创意写作与叙事、深度调研、Agent 技能与自动化，以及人机协作方法。

### 参与贡献与日常维护

新增内容请说明真实问题、可复用方法、技术条件、人工验证到哪里、可能在哪些场景失效，以及版本号。早期试验注明实验性质。只纳入适合公开的内容，并按需检查授权和署名。

完整流程放到 `workflows/`，单项提示词放到 `prompts/`，经过验证的 Agent 模块放到 `skills/`，可运行代码放到 `tools/`，项目复盘放到 `case-studies/`。首份内容就绪时再创建对应目录。更新中英文索引和相关日志，用 `git diff` 检查，以 `git add <路径>` 暂存相关文件，提交后推送分支。发布版本时为通过检查的提交打标签，并根据更新日志撰写双语发布说明。

### 许可

仓库中的文档、工作流和提示词由 Lune 在有权授权的范围内按 [CC BY 4.0](LICENSE) 发布。复制、改编或商用时，请署名 Lune、附上许可链接并注明修改。第三方内容仍适用各自的使用条款。

### 关于

由 **Lune** 维护，始于 2026 年 11 月 24 日。

*做出作品，从中学习，保存方法，分享可能性。*
