<div align="center">

# 🚀 best-prompts

**A curated arsenal of battle-tested AI prompts — copy, paste, and get expert-level output.**

*From thesis writing to production code, from system diagrams to viral articles — 29 scenario-specific prompts engineered with careful constraints, not generic templates.*

[![License](https://img.shields.io/badge/License-Apache_2.0-blue.svg)](LICENSE) [![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](../../pulls) [![Prompts](https://img.shields.io/badge/prompts-29-orange.svg)](prompts/)

</div>

---

## ✨ Why this repo?

In the age of vibe coding, **the quality of your prompt determines the quality of AI's output**. Most "universal" prompts are either too generic or too scattered. Every prompt here is:

- 🎯 **Scenario-specific** — designed for one job and tuned for it, with output format and constraints built in
- 📋 **Copy-and-go** — paste straight into ChatGPT, Claude, Gemini, Cursor, or any agent — no endless tweaking
- 🗂️ **Organized by use case** — find what you need by task, not by digging through files
- ✅ **Verified on frontier models** — works great on Claude, GPT, Gemini and coding agents

## 🧭 What's inside

| Category | What you get |
| --- | --- |
| 🎓 **Thesis writing** | Full degree-thesis workflow: outline review, chapter drafting, polishing, references, anti-AIGC, CN↔EN translation |
| 📊 **Diagrams as code** | Draw.io / Excalidraw generators: system architecture, E-R, tech stack, data structures, style migration |
| 💻 **5-step dev workflow** | Requirement → Design → Implementation → Review → Bug fix, one prompt per step |
| ✍️ **Content creation** | WeChat/blog article writing with 9 writing styles + style extraction, covers and illustrations |
| 📁 **Docs & resume** | Project overviews, key-issue digests, resume-ready project descriptions |
| 📈 **Reports** | Weekly reports, work reports, retrospectives, intros — from fragmented notes to polished docs |
| 🎨 **Frontend design** | Production-grade UI code with a strong aesthetic stance — no "generic AI look" |
| 🔧 **Tools & skills** | Multi-language code review, Skill creation, Skill ↔ Prompt conversion |

## ⚡ Quick start

1. Open the `.md` file for your scenario in [`prompts/`](prompts/)
2. Copy the full prompt (from `# Role` to `# Input`, code blocks included)
3. Paste it into your AI chat
4. Fill in your content at the `[在此处填写]` placeholders — done

> 💡 Using Cursor, Claude Code, or another agent? Most scenarios also exist as auto-invoked **Skills**: [best-skills](https://github.com/xstongxue/best-skills)

## 🙏 Credits

Forked from [xstongxue/best-prompts](https://github.com/xstongxue/best-prompts) — all credit to the original author. Licensed under [Apache 2.0](LICENSE).

---

<br>

# 中文完整目录 · Full Catalog (中文)


# best-prompts🚀

通用高质量 prompt 合集，可直接复制到聊天框使用。

本提示词在 Claude4.6、Gemini3、GPT5.2、Composer1.5 等模型下遵循极好，优先推荐使用

更多模型排名：[https://arena.ai/zh/leaderboard](https://arena.ai/zh/leaderboard)

> 💡 如果你使用 Cursor、Claude Code、OpenClaw 等 Agent 工具，本仓库的大部分场景都有对应的 **Skill 版本**，无需手动复制粘贴，Agent 会自动识别并调用：
> 👉 [best-skills](https://github.com/xstongxue/best-skills)

## 一 项目初衷

在 Vibe Coding 时代，**好的 Prompt 决定 AI 的输出质量**。但市面上很多「万能写作 Prompt」要么太泛、要么太散——真正能贴合具体场景、适配输出格式、兼顾约束细节的，少之又少。

best-prompts 希望做两件事：

> 1. **沉淀可复用的高质量 Prompt**：每个 Prompt 都经过场景细分和约束设计，复制即用，减少反复调试
> 2. **按使用场景组织**：从论文撰写、开发流程到自媒体创作，让用户按需找到对应 Prompt，而非在零散文件中翻找

项目**通用且可扩展**，会持续补充更多领域。欢迎 Star、Fork、提 Issue 和 PR。

## 二 按使用场景分类

### 本科&硕士学位论文撰写

学位论文全流程（大纲审核、结构仿写、润色扩写、参考文献、防 AIGC、中英互译等），配合图表生成完成系统设计章节的图文内容。


| 用途         | Prompt                                                                                                                           |
| ---------- | -------------------------------------------------------------------------------------------------------------------------------- |
| **正文内容撰写** | [paper-write-prompt.md](prompts/paper-write-prompt.md) — 大纲审核、绪论/摘要/章节仿写、问题与格式检查、润色/扩写/缩写、参考文献、防 AIGC、中英互译、结构化信息提取                     |
| **系统章节生成** | [codegen-paper-chapter-generator-prompt.md](prompts/codegen-paper-chapter-generator-prompt.md) — 根据大纲与项目代码生成系统设计章节正文             |
| **通用图表**   | [drawio-diagram-generator-prompt.md](prompts/drawio-diagram-generator-prompt.md) — 模型架构图、算法流程图、概念示意图                             |
| **技术栈图**   | [codegen-tech-stack-diagram-prompt.md](prompts/codegen-tech-stack-diagram-prompt.md) — 前端/后端/模型服务技术栈结构图                          |
| **系统架构图**  | [codegen-system-arch-diagram-prompt.md](prompts/codegen-system-arch-diagram-prompt.md) — 四层分层架构图                                 |
| **数据结构图**  | [codegen-data-structure-diagram-prompt.md](prompts/codegen-data-structure-diagram-prompt.md) — 表格式实体与字段关系图                       |
| **E-R 图**  | [codegen-er-diagram-prompt.md](prompts/codegen-er-diagram-prompt.md) — Chen 记法实体关系图                                              |
| **图片风格迁移** | [diagram-style-migration-prompt.md](prompts/diagram-style-migration-prompt.md) — 参考图 + 内容描述/项目，按参考图风格生成新图表                       |
| **答辩 PPT** | [pptgen-drawio-paper-defense-prompt.md](prompts/pptgen-drawio-paper-defense-prompt.md) — 多页 Draw.io 生成，配合 drawio2pptx 导出可编辑的 PPT |


### 投稿小论文撰写

期刊/会议论文写作，推荐使用外部精选资源：

- [awesome-ai-research-writing](https://github.com/Leey21/awesome-ai-research-writing) — AI 辅助学术写作工具与 Prompt 汇总

### 开发流程五步法

需求理解 → 方案设计 → 代码实现 → 代码审查 → Bug 修复。


| 步骤      | Prompt                                                                   |
| ------- | ------------------------------------------------------------------------ |
| 需求理解    | [dev-requirement-prompt.md](prompts/dev-requirement-prompt.md)           |
| 方案设计    | [dev-design-prompt.md](prompts/dev-design-prompt.md)                     |
| 代码实现    | [dev-implementation-prompt.md](prompts/dev-implementation-prompt.md)     |
| 代码审查    | [dev-review-prompt.md](prompts/dev-review-prompt.md)                     |
| Bug 修复  | [dev-bug-fix-prompt.md](prompts/dev-bug-fix-prompt.md) — 按优先级列出多种方案，自动逐一尝试，解决即停 |


### 自媒体创作


| 用途              | Prompt                                                                                                                                                 |
| --------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------ |
| 公众号/技术博客        | [wechat-article-write-prompt.md](prompts/wechat-article-write-prompt.md) — 搜索资料、撰写、爆款标题、排版优化；**集成 9 种写作风格 + 风格提取**（从样本文章提取可复用规则与 Prompt），按需复制对应 Prompt |
| 公众号封面 Draw.io   | [wechat-article-image-generator-prompt.md](prompts/wechat-article-image-generator-prompt.md) — 封面/结尾图 .drawio XML，默认合并封面（1283×383），支持大封面 900×383、小封面 383×383、16:9、9:16      |
| 公众号文章插图 Draw.io | [wechat-article-illustration-prompt.md](prompts/wechat-article-illustration-prompt.md) — 正文插图 .drawio XML，步骤图、演示图、流程示意、前后对比                            |


### 项目文档与简历


| 用途     | Prompt                                                                               |
| ------ | ------------------------------------------------------------------------------------ |
| 项目整体梳理 | [codegen-project-overview-prompt.md](prompts/codegen-project-overview-prompt.md)     |
| 项目重点问题 | [codegen-project-key-issues-prompt.md](prompts/codegen-project-key-issues-prompt.md) |
| 简历项目描述 | [codegen-resume-format-prompt.md](prompts/codegen-resume-format-prompt.md)           |


### 周报 / 汇报 / 总结 / 介绍

将工作草稿、碎片笔记或背景信息整理为结构清晰、数据精准、有结论的高质量文档。


| 用途         | Prompt                                                                                               |
| ---------- | ---------------------------------------------------------------------------------------------------- |
| 周报         | [doc-weekly-report-prompt.md](prompts/doc-weekly-report-prompt.md) — 碎片草稿 → 标准周报，含本周完成/进行中/下周计划/问题风险 |
| 工作汇报       | [doc-work-report-prompt.md](prompts/doc-work-report-prompt.md) — 结论前置，进展状态标签（✅/🔄/⏳），关键成果与协调事项       |
| 工作总结 / 复盘  | [doc-summary-report-prompt.md](prompts/doc-summary-report-prompt.md) — 背景目标、量化成果、根因分析、可复用经验方法论       |
| 项目/产品/个人介绍 | [doc-introduction-prompt.md](prompts/doc-introduction-prompt.md) — 一句话定位、核心能力对比表、差异化优势、具体适用场景        |


### 前端界面设计

创建具有高设计品质、可交付生产的前端界面，规避「AI 通用审美」，产出有创意、打磨到位的代码与设计。


| 用途 | Prompt |
| --- | --- |
| 前端界面设计 | [frontend-design-prompt.md](prompts/frontend-design-prompt.md) — Web 组件/页面/应用，有强烈美学立场的前端实现，规避 AI 通用审美 |


### 工具与扩展


| 用途                | Prompt                                                                       |
| ----------------- | ---------------------------------------------------------------------------- |
| 代码审查（多语言）         | [code-review-excellence-prompt.md](prompts/code-review-excellence-prompt.md) |
| Skill 创建          | [skill-create-prompt.md](prompts/skill-create-prompt.md)                     |
| Skill 与 Prompt 互转 | [skill-prompt-convert-prompt.md](prompts/skill-prompt-convert-prompt.md)     |


---

## 三 使用方式

> 1. 打开对应 `.md` 文件
> 2. 复制 `# Role` 到 `# Input` 之间的完整 Prompt（含  代码块）
> 3. 粘贴到与 AI 的对话中
> 4. 在 `[在此处填写]` 或 `[在此处粘贴]` 位置填入你的内容