# FounderOS

FounderOS 是一个开源的、Markdown 优先的创业者操作系统，用来帮助创始人捕捉创业想法、研究市场、澄清用户问题、设计产品，并把关键假设推进到实验验证。

它适合用 Obsidian、VS Code、Cursor 或任意 Markdown 编辑器打开，也适合和 AI agent 一起使用。

## 适合谁

- 正在探索创业方向的独立创始人
- 正在验证市场或 MVP 的产品构建者
- 需要整理用户问题和实验记录的 indie hacker
- 希望用轻量系统替代复杂创业工具的人
- 想让 AI agent 参与创业思考和资料整理的人

## 核心思想

很多创业笔记会混在一起：

- 原始灵感
- 真实用户问题
- 市场观察
- 产品构思
- 验证证据

FounderOS 把它们拆开，让每个想法都能向前推进：

```text
idea -> problem -> market -> product -> business model -> experiment -> decision
```

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
2. 用 Obsidian、VS Code、Cursor 或任意 Markdown 编辑器打开 `FounderOS/`。
3. 把所有未整理想法先放进 `00-Inbox/`。
4. 想法变清晰后，从 `templates/` 复制模板到对应目录。
5. 用 `07-Experiments/` 把关键假设转成可验证实验。

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

在 `07-Experiments/` 里写清楚：

- 要验证的假设
- 实验方式
- 成功标准
- 实验结果
- 下一步决策

### 5. 复盘

在 `06-Founder-Notes/` 里记录创始人复盘、决策日志和长期原则。

## 模板

可以从这些文件开始：

- `templates/idea.md`
- `templates/problem.md`
- `templates/experiment.md`
- `templates/market-research.md`
- `templates/business-model.md`

复制模板到对应目录，重命名后填写即可。

## 示例

查看 `examples/ai-study-planner/`，里面展示了一个想法如何经过：

- idea
- 用户问题
- 市场研究
- 商业模式
- 验证实验

## 和 AI Agent 一起使用

FounderOS 对 AI agent 友好。项目级协作说明在 `AGENTS.md`。

你可以让 AI assistant 帮你：

- 整理 `00-Inbox/` 里的原始笔记
- 把想法拆成可验证假设
- 从访谈记录中提取用户问题
- 设计有明确成功标准的实验
- 对比市场研究笔记并找出开放问题

## 原则

1. 先捕捉，再整理。
2. 想法还不确定时，保留原始语境。
3. 区分事实、判断和假设。
4. 证据比自信更重要。
5. 重要想法最终都应该进入实验。
6. 笔记是为了帮助决策，不是为了收藏。

## 贡献

欢迎贡献：

- 更好的模板
- 更完整的示例
- 创始人工作流
- AI agent 协作说明
- 翻译
- Obsidian 使用改进

详见 `CONTRIBUTING.md`。

## License

MIT License. See `LICENSE`.
