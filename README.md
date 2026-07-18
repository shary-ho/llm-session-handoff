**Agent skill**
# llm-session-handoff
## 大模型会话迁移助手（LLM Session Handoff）

当一个 AI 无法继续完成你的项目，或者你希望将当前工作迁移到另一个大模型（如 ChatGPT、Claude、Gemini、Qwen、DeepSeek 等）时，这个 Skill 可以帮助你一键完成项目交接。

它会自动梳理当前会话和项目内容，提取真正有价值的信息，并生成一份结构化的迁移包（Migration Package），包括：

* 📌 项目背景与目标
* 📌 当前开发进度与项目状态
* 📌 核心设计决策及原因
* 📌 已验证方案与失败尝试（避免重复踩坑）
* 📌 AI 在协作过程中出现过的问题和易错点
* 📌 用户的开发偏好与约束条件
* 📌 重要文件、技术栈、待办事项（TODO）
* 📌 可直接发送给另一个大模型的 Resume Prompt

迁移后的 AI 无需阅读大量历史对话，即可快速理解项目背景、接续已有工作，大幅减少重复沟通和上下文丢失，让跨模型协作更加高效。

### 适用场景

* 🔄 从 ChatGPT 迁移到 Claude（或其他大模型）
* 🔄 因上下文过长，需要开启新会话继续开发
* 🔄 项目交接给其他开发者或 AI
* 🔄 保存项目阶段性成果，方便后续继续开发
* 🔄 长周期项目的上下文归档与恢复

### 使用方式

在准备结束当前会话或切换模型时，直接调用本 Skill。
Skill 会自动分析当前项目，生成完整的迁移文档和交接信息。将生成的迁移包发送给新的大模型，即可让其快速接手项目并继续工作，无需重新解释需求或重复讨论已完成的内容。

---

这版既符合 SkillHub 的展示风格，也清楚地回答了用户最关心的三个问题：

1. **它是干什么的？**——解决大模型之间的项目/会话迁移问题。
2. **什么时候用？**——切换模型、开新会话、项目交接、长期项目归档。
3. **用了之后有什么价值？**——保留上下文、避免重复沟通、让新的 AI 无缝接手。


# llm-session-handoff
## LLM Session Handoff
When your current AI assistant can no longer continue your project, or you want to switch to another large language model (such as ChatGPT, Claude, Gemini, Qwen, DeepSeek, etc.), this Skill helps you seamlessly hand off your work with a single command.

It automatically analyzes your current conversation and project, extracts the information that truly matters, and generates a structured **Migration Package** containing:

- 📌 Project overview and objectives
- 📌 Current progress and project status
- 📌 Key design decisions and the reasoning behind them
- 📌 Validated solutions and failed attempts (to avoid repeating mistakes)
- 📌 Common AI mistakes and collaboration pitfalls encountered during development
- 📌 User preferences and project constraints
- 📌 Important files, technology stack, and open TODOs
- 📌 A ready-to-use **Resume Prompt** for another LLM

With the generated Migration Package, a new AI model can quickly understand your project and continue working without reading lengthy conversation histories. This significantly reduces repeated explanations, prevents context loss, and enables efficient cross-model collaboration.

## Use Cases

- 🔄 Switch from ChatGPT to Claude (or any other LLM)
- 🔄 Continue development in a new conversation when the context window is full
- 🔄 Hand off a project to another developer or AI assistant
- 🔄 Save project milestones for future development
- 🔄 Archive and restore context for long-running projects

## How to Use

Simply invoke this Skill before ending your current conversation or switching to another AI model.

The Skill will analyze your current project, generate a complete Migration Package, and prepare all the information required for a seamless handoff. Send the generated package to your new AI assistant, and it can immediately continue the project without requiring you to repeat requirements or revisit previous discussions.

## Why Use This Skill?

This Skill is designed to solve three common problems when working with multiple AI models:

- **Preserve context** – Keep essential project knowledge instead of losing it when starting a new conversation.
- **Eliminate repetitive explanations** – Avoid explaining the same project multiple times to different AI models.
- **Enable seamless handoffs** – Allow another AI assistant to pick up exactly where the previous one left off.
