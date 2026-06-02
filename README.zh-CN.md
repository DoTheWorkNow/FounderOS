# FounderOS

[English](README.md) | [中文](README.zh-CN.md)

FounderOS 是一个开源的、Markdown 优先的创业者操作系统，用来帮助创始人捕捉创业想法、澄清用户问题、研究市场、设计产品，并把关键假设推进到实验验证。

它适合用 Obsidian、VS Code、Cursor、GitHub 或任意 Markdown 编辑器打开，也适合和 AI agent 一起使用。

## 为什么需要 FounderOS

早期创业工作天然混乱。很多笔记会把灵感、用户痛点、市场观察、产品方案和验证证据混在一起，时间一长就很难判断：什么是真实发生的，什么只是自己的判断，什么还需要验证。

FounderOS 给这些想法一个简单的操作结构：

```text
idea -> problem -> market -> product -> business model -> experiment -> decision
```

它的目标不是让你写更多文档，而是帮助你做出更好的创业判断。

## 你可以用它做什么

- 捕捉原始创业想法，避免过早包装
- 把模糊想法拆成清晰用户问题
- 区分事实、判断和假设
- 沉淀可复用的市场和竞品研究
- 从真实痛点出发设计 MVP 和产品概念
- 在商业模式变成“自信幻觉”前记录关键假设
- 用明确成功标准推进验证实验
- 让 AI agent 帮你整理、追问和改进创业思考

## 适合谁

- 正在探索创业方向的独立创始人
- 正在验证市场或 MVP 的产品构建者
- 需要整理用户问题和实验记录的 indie hacker
- 希望用轻量系统替代复杂创业工具的人
- 想让 AI agent 参与创业思考和资料整理的人

## 目录结构

```text
FounderOS/
├── 00-Inbox/            # 临时收集箱：原始想法、快速记录、未整理内容
├── 01-Ideas/            # 创业想法：机会、假设、灵感、方向
├── 02-Problems/         # 用户问题：痛点、场景、未满足需求
├── 03-Market/           # 市场研究：趋势、竞品、行业结构
├── 04-Products/         # 产品构思：MVP、用户路径、产品文档
├── 05-Business-Models/  # 商业模式：定价、渠道、收入模型、单位经济
├── 06-Founder-Notes/    # 创始人笔记：复盘、决策、原则、认知
├── 07-Experiments/      # 实验验证：访谈、MVP 测试、数据、结论
├── 08-Resources/        # 资料库：文章、书籍、案例、工具、课程
├── templates/           # 可复制使用的模板
├── examples/            # 已填好的示例
├── docs/                # 额外文档
├── AGENTS.md            # AI agent 协作说明
└── README.md
```

## 快速开始

1. Clone 或下载这个仓库。
2. 用 Obsidian、VS Code、Cursor 或任意 Markdown 编辑器打开这个文件夹。
3. 把所有未整理想法先放进 `00-Inbox/`。
4. 从 `templates/` 复制模板到对应目录。
5. 用 `07-Experiments/` 把重要假设转成验证实验。

## 模板

FounderOS 内置这些可复用模板：

| 模板 | 用途 |
| --- | --- |
| [idea.md](templates/idea.md) | 记录创业想法和关键假设 |
| [problem.md](templates/problem.md) | 描述真实用户问题 |
| [market-research.md](templates/market-research.md) | 研究市场、品类或竞品格局 |
| [business-model.md](templates/business-model.md) | 思考定价、渠道、收入和单位经济 |
| [experiment.md](templates/experiment.md) | 设计带成功标准的验证实验 |

## 示例工作流

查看 [examples/ai-study-planner](examples/ai-study-planner/)，里面有一个已经填好的示例。

这个示例展示一个想法如何经过：

```text
AI Study Planner
├── idea.md
├── problem.md
├── market-research.md
├── business-model.md
└── experiment.md
```

这就是 FounderOS 的基本节奏：从想法开始，澄清问题，理解市场，推演商业模式，然后验证风险最高的假设。

## 和 AI Agent 一起使用

FounderOS 对 AI agent 友好。项目级协作说明在 [AGENTS.md](AGENTS.md)。

你可以让 AI assistant 帮你：

- 整理 `00-Inbox/` 里的原始笔记
- 把想法拆成可验证假设
- 从访谈记录中提取用户问题
- 设计有明确成功标准的实验
- 对比市场研究笔记并找出开放问题
- 建议下一步最小验证动作

## 推荐工作流

### 1. 捕捉

所有未成形内容先放进 `00-Inbox/`。早期不要急着分类和包装。

### 2. 澄清

根据内容移动到：

- `01-Ideas/`：可能的创业方向
- `02-Problems/`：真实用户痛点
- `03-Market/`：市场、竞品、趋势、行业结构

### 3. 成形

使用：

- `04-Products/`：产品概念、MVP、用户路径
- `05-Business-Models/`：定价、获客、渠道、收入逻辑

### 4. 验证

在 `07-Experiments/` 里写清楚要验证的假设、实验方式、成功标准、实验结果和下一步决策。

### 5. 复盘

在 `06-Founder-Notes/` 里记录创始人复盘、决策日志和长期原则。

## 原则

1. 先捕捉，再整理。
2. 想法还不确定时，保留原始语境。
3. 区分事实、判断和假设。
4. 证据比自信更重要。
5. 重要想法最终都应该进入实验。
6. 笔记是为了帮助决策，不是为了收藏。

## 路线图

- 增加更多不同类型创始人工作流示例
- 增加中文优先模板
- 增加 Obsidian 使用指南
- 增加用户访谈模板
- 增加创始人周复盘模板
- 为非技术用户提供更轻量的下载包

## 贡献

欢迎贡献更好的模板、更完整的示例、创始人工作流、AI agent 协作说明、翻译和 Obsidian 使用改进。

详见 [CONTRIBUTING.md](CONTRIBUTING.md)。

## License

MIT License. See [LICENSE](LICENSE).
