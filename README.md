# AI4Everyone

> 零门槛拥抱智能时代——AI 技术的系统性理解，不属于任何一家公司，属于每个愿意学习的人。

AI 正在重塑每个人与技术的关系。这个项目收集和整理高质量的中文 AI 技术文档，覆盖从工具选型到架构设计的完整链条。无论你是工程师、设计师、产品经理还是学生，都能在这里找到有用的信息。

## 📚 文档

### 1. AI 编程工具深度解析：全面对比与选型指南

> 更新至 2026 年 5 月 | 覆盖 13+ 工具、6 大核心技术

从 CLI 到桌面应用，从国际 IDE 到国产 IDE，从 IDE 扩展到多 Agent 编排——一份文档帮你搞清楚该用什么、怎么用。

**覆盖的工具**：Claude Code、Codex CLI、OpenCode、Gemini CLI、Claude Code Desktop、Codex Desktop、Cursor、Windsurf、Augment Code、Trae、通义灵码、CodeBuddy、GitHub Copilot、Cline、Roo Code、Continue

**核心技术深度解析**：MCP（Model Context Protocol）、Agent Skills、Sub-agents 与 Agent Teams 编排、A2A 协议、Auto Dream 记忆巩固、Worktree 隔离

### 2. AI Agent 开发范式转移：从手写代码到声明式定义

> 覆盖 2023–2026 年 | 17 篇论文、5 个行业标准、主流工具与代码库

Agent 开发正经历从"写代码描述如何做"到"写配置描述要什么"的范式转移——意义不亚于从汇编到高级语言的跃迁。这份文档系统梳理了转变的技术脉络、关键论文、工业标准和代表性工具。

**三个阶段**：代码优先（2023–2024）→ 声明式定义（2025）→ 标准化与互操作（2026）

---

## 📊 速览：关键对比表

### CLI 工具对比

| 维度 | Claude Code | Codex CLI | OpenCode | Gemini CLI |
|------|:-----------:|:---------:|:--------:|:----------:|
| 发布方 | Anthropic | OpenAI | 开源社区 | Google |
| 开源 | ❌ | ✅ Apache 2.0 | ✅ | ✅ Apache 2.0 |
| 默认模型 | Claude Opus 4.7 | codex-mini (可选 GPT-5.x) | 任意 75+ 模型 | Gemini 2.5/3 |
| 最大上下文 | 1M tokens | ~272K–1M+ | 取决于模型 | 1M tokens |
| MCP | ✅ | ✅ | ✅ 原生 | ✅ |
| 多 Agent | Sub-agents | 并行工具调用 | Agents + Subagents | ReAct 循环 |
| 项目约定 | CLAUDE.md | AGENTS.md | AGENTS.md | GEMINI.md |
| 定价 | $20–200/月 | $20/月起 | 免费 + API | 免费额度 |

### 模型基准对比（2026 Q2）

| 基准测试 | Claude Opus 4.7 | GPT-5.5 | Gemini 3.1 Pro |
|----------|:---------------:|:-------:|:--------------:|
| SWE-Bench Verified | **87.6%** | ~82–85% | ~80.6% |
| SWE-Bench Pro | **64.3%** | 58.6% | — |
| Terminal-Bench 2.0 | 69.4% | **82.7%** | — |
| 最适合 | 精确编码、多文件重构 | 自主终端任务、DevOps | 多模态推理、大上下文 |

### Agent 开发范式对比

| 维度 | 代码优先（2023–2024） | 声明式定义（2025） | 标准化互操作（2026） |
|------|:---:|:---:|:---:|
| 代表工具 | LangGraph, CrewAI | Claude Code Agents | Open Agent Spec |
| 定义方式 | Python 类和方法 | Markdown + YAML | YAML/JSON Schema |
| 非开发者可参与 | ❌ | ✅ | ✅ |
| 运行时绑定 | 强绑定 | 弱绑定 | 无绑定 |
| 学习成本 | 高 | 低 | 低–中 |

### 核心技术演进

| 技术 | 2024 | 2025 | 2026 Q2 |
|------|------|------|---------|
| **MCP** | 发布 | 广泛采用 | 行业标准（14K+ Server） |
| **Agent Skills** | — | 概念提出 | 跨平台落地（SKILL.md） |
| **A2A 协议** | — | 发布 v1 | 150+ 组织生产采用 |
| **Auto Dream** | 学术研究 | Sleep-time Compute 论文 | 生产化（Claude Code） |
| **Agent 编排** | 实验阶段 | LangGraph 主导 | 多范式并存 |

---

## 🎯 选型速查

| 你的场景 | 推荐工具 |
|---------|---------|
| 终端重度用户 | Claude Code CLI |
| 开源 + 隐私优先 | OpenCode + Cline |
| 全功能 AI IDE | Cursor |
| 大型项目 / 多代理协作 | Windsurf / Augment Code |
| 不想换编辑器 | GitHub Copilot + Cline |
| 预算有限 | OpenCode + Cline + Continue（全开源） |
| 国内开发 / 中文优先 | 通义灵码 + Trae |
| 微信小程序 | CodeBuddy（腾讯） |
| 企业合规 / 私有部署 | 通义灵码 / CodeBuddy 企业版 |

---

## 🤔 为什么做这个

AI 工具和框架的迭代速度远超传统软件。大多数人面对的信息要么是营销话术，要么是碎片化的技术推文，很难形成系统认知。这个项目试图提供一个中间地带：

- **准确**：所有技术声明追溯官方文档和一手来源，标注引用链接
- **完整**：横向覆盖多个工具/技术，纵向从概念到实践
- **可操作**：不是"了解一下"，而是能帮你做出选择
- **中文优先**：降低中文用户获取前沿 AI 技术信息的门槛

## 🤝 贡献

如果你发现内容有误或过时，欢迎提 Issue 或 PR。好的技术文档需要持续维护。

## 📄 License

MIT
