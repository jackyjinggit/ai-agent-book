# ai-agent-book 工程方法论导读（本 fork 增量）

> 本 fork 是李博杰《深入理解 AI Agent：设计原理与工程实践》的**工程方法论导读层（AI Agent / Harness 工程视角）**。
> 不搬运正文（正文见上游 [bojieli/ai-agent-book](https://github.com/bojieli/ai-agent-book)），
> 只添加「读后提炼」——把章节内容加工成可直接复用的工程方法论文档（框架 / 判据 / 清单），并附与生产实践的对照。
> 定位：把 Harness 工程从教材讲明白到能落地——第 2/4/5/7 章笔记对应上下文工程、工具（MCP）、Coding Agent、评估归因，构成 Agent/Harness 工程的知识地图。
> 笔记为独立加工产物（Apache-2.0），内容提炼自原书（亦 Apache-2.0），不替代阅读原书。

## 为什么需要这份增量

原著 10 章是教材体例，信息密度高，但「怎么用」散落在配套实验里。
本 fork 把每章压缩为「核心认知 → 可操作框架 → 常见坑 → 工程判据」四段式，
适合**已读完正文、要落地实践**的读者——从「读懂了」到「用得上」。

## 笔记清单

| 章节 | 主题 | 笔记 | 状态 |
|---|---|---|---|
| 第 1 章 | AI Agent 入门 | [chapter01-intro.md](./chapter01-intro.md) | ✅ 已完成 |
| 第 2 章 | 上下文工程 | [chapter02-context-engineering.md](./chapter02-context-engineering.md) | ✅ 已完成 |
| 第 3 章 | 用户记忆和知识库 | [chapter03-memory-and-knowledge.md](./chapter03-memory-and-knowledge.md) | ✅ 已完成 |
| 第 4 章 | 工具（MCP） | [chapter04-tools.md](./chapter04-tools.md) | ✅ 已完成 |
| 第 5 章 | Coding Agent 与代码生成 | [chapter05-coding-agent.md](./chapter05-coding-agent.md) | ✅ 已完成 |
| 第 6 章 | 交互：观察与动作空间的扩展 | [chapter06-interaction.md](./chapter06-interaction.md) | ✅ 已完成 |
| 第 7 章 | Agent 的评估 | [chapter07-evaluation.md](./chapter07-evaluation.md) | ✅ 已完成 |
| 第 8 章 | 模型后训练 | [chapter08-post-training.md](./chapter08-post-training.md) | ✅ 已完成 |
| 第 9 章 | Agent 的持续进化 | [chapter09-evolution.md](./chapter09-evolution.md) | ✅ 已完成 |
| 第 10 章 | 多 Agent 协作 | [chapter10-multi-agent.md](./chapter10-multi-agent.md) | ✅ 已完成 |

> 覆盖：10/10 章（第 7、9 章为深度精读版，其余为结构精读版，格式统一四段式）。

## 写作格式（每篇固定四段式）

1. **核心认知**：本章 3-5 条「金句级」结论，可直接引用
2. **可操作框架**：表格化框架（指标体系 / 验证层 / 载体判据等），能直接照做
3. **常见坑**：作者反复强调的陷阱 + 实测解法
4. **工程判据**：从「什么时候用、怎么选、怎么防自证」角度给的决策清单

## 贡献

欢迎 PR：任一章的精读笔记 / 实验复现 / 踩坑记录。要求：

- 不搬运原书正文，只做提炼与加工
- 标注对应的原书章节与实验编号
- 可独立使用（不依赖本仓库其他文件）
