![FLOW Method](banner-flow-method.png)

[![Version](https://img.shields.io/npm/v/@flownetbr/flow-method?color=blue&label=version)](https://www.npmjs.com/package/@flownetbr/flow-method)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Node.js Version](https://img.shields.io/badge/node-%3E%3D20.0.0-brightgreen)](https://nodejs.org)

**突破性敏捷 AI 驱动开发方法** — 简称 “FLOW 方法论”。FLOW 方法论是由多个模块生态构成的 AI 驱动敏捷开发模块系统，这是最佳且最全面的敏捷 AI 驱动开发框架，具备真正的规模自适应人工智能，可适应快速开发，适应企业规模化开发。

> **本项目是 [EVO Method](https://github.com/evolution-foundation/EVO-METHOD) 的独立分支（fork）**，而 EVO 本身源自 [BMad Method](https://github.com/bmad-code-org/BMAD-METHOD) — 独立维护，并包含自有的改进与调整。

**100% 免费且开源。** 无付费。无内容门槛。我们赋能每个人，我们将为全球现在在人工智能领域发展的普通人提供公平的学习机会。

## 为什么选择 FLOW 方法？

传统 AI 工具替你思考，产生平庸的结果。FLOW 智能体和辅助工作流充当专家协作者，引导你通过结构化流程，与 AI 的合作发挥最佳思维，产出最有效优秀的结果。

- **AI 智能帮助** — 随时使用 `/flow-help` 获取下一步指导
- **规模-领域自适应** — 根据项目复杂度自动调整规划深度
- **结构化工作流** — 基于分析、规划、架构和实施的敏捷最佳实践
- **专业智能体** — 12+ 领域专家（PM、架构师、开发者、UX、Scrum Master 等）
- **派对模式** — 将多个智能体角色带入一个会话进行协作和讨论
- **完整生命周期** — 从想法开始（头脑风暴）到部署发布

---

## 快速开始

**先决条件**：[Node.js](https://nodejs.org) v20+

```bash
npx @flownetbr/flow-method@latest install
```

按照安装程序提示操作，然后在项目文件夹中打开你的 AI IDE（Claude Code、Cursor 等）。

**非交互式安装**（用于 CI/CD）：

```bash
npx @flownetbr/flow-method install --directory /path/to/project --modules bmm --tools claude-code --yes
```

> **不确定该做什么？** 运行 `/flow-help` — 它会准确告诉你下一步做什么以及什么是可选的。你也可以问诸如 `/flow-help 我刚刚完成了架构设计，接下来该做什么？` 之类的问题。

## 模块

FLOW 方法通过官方模块扩展到专业领域。可在安装期间或之后的任何时间使用。

| Module                                                                                                                                    | Purpose                                           |
| ----------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------- |
| **[FLOW Method (BMM)](https://github.com/SylvioNetoRj/FLOW-METHOD)**                                                                      | 包含 34+ 工作流的核心框架                         |
| **[BMad Builder (BMB)](https://github.com/bmad-code-org/bmad-builder)**                                                                   | 创建自定义智能体和工作流                          |
| **[Test Architect (TEA)](https://github.com/bmad-code-org/bmad-method-test-architecture-enterprise)**                                     | 基于风险的测试策略和自动化                         |
| **[Game Dev Studio (GDS)](https://github.com/bmad-code-org/bmad-module-game-dev-studio)**                                                 | 游戏开发工作流（Unity、Unreal、Godot）             |
| **[Creative Intelligence Suite (CIS)](https://github.com/bmad-code-org/bmad-module-creative-intelligence-suite)**                        | 创新、头脑风暴、设计思维                           |

## 文档

[BMad Method 文档站点（上游）](https://docs.bmad-method.org) — 教程、指南、概念和参考

## 社区

- [GitHub Issues](https://github.com/SylvioNetoRj/FLOW-METHOD/issues) — 错误报告和功能请求
- [讨论](https://github.com/SylvioNetoRj/FLOW-METHOD/discussions) — 社区对话

## 支持 FLOW

FLOW 对每个人都是免费的 — 并且永远如此。如果你想支持开发：

- ⭐ 请点击此页面右上角附近的项目星标图标

## 贡献

我们欢迎贡献！请参阅 [CONTRIBUTING.md](CONTRIBUTING.md) 了解指南。

## 许可证

MIT 许可证 — 详见 [LICENSE](LICENSE)。

---

**注：** 本项目是独立分支。“BMad” 和 “BMad Method” 是 BMad Code, LLC 的商标；“EVO” 和 “EVO Method” 是 EVO Code, LLC 的商标。这些商标不受 MIT 许可证约束。详见 [TRADEMARK.md](TRADEMARK.md)。

[![Contributors](https://contrib.rocks/image?repo=SylvioNetoRj/FLOW-METHOD)](https://github.com/SylvioNetoRj/FLOW-METHOD/graphs/contributors)

---
## 术语说明

- **agent**：智能体。在人工智能与编程文档中，指具备自主决策或执行能力的单元。
- **workflow**：工作流。指一系列有序的任务或步骤，用于完成特定目标。
- **CI/CD**：持续集成/持续部署。一种自动化软件开发实践，用于频繁集成代码更改并自动部署。
- **IDE**：集成开发环境。提供代码编辑、调试、构建等功能的软件开发工具。
- **PM**：产品经理。负责产品规划、需求管理和团队协调的角色。
- **UX**：用户体验。指用户在使用产品或服务过程中的整体感受和交互体验。
- **Scrum Master**：Scrum 主管。敏捷开发 Scrum 框架中的角色，负责促进团队遵循 Scrum 流程。
- **PRD**：产品需求文档。详细描述产品功能、需求和规格的文档。
