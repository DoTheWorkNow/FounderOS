# FounderOS

[English](README.md) | [中文](README.zh-CN.md)

FounderOS is an open, Markdown-first operating system for founders. It helps you capture ideas, clarify customer problems, study markets, design products, and turn assumptions into experiments.

It is built for founders who want a lightweight knowledge base that works well with Obsidian, VS Code, Cursor, GitHub, and AI agents.

## Why FounderOS

Early-stage startup work is messy. Notes often mix inspiration, customer pain, market research, product ideas, and validation evidence in one place. That makes it hard to know what is real, what is assumed, and what should be tested next.

FounderOS gives those thoughts a simple operating structure:

```text
idea -> problem -> market -> product -> business model -> experiment -> decision
```

The goal is not to create more documents. The goal is to make better founder decisions.

## What You Can Do With It

- Capture raw startup ideas without over-organizing too early
- Turn vague ideas into clear customer problems
- Separate facts, judgments, and hypotheses
- Keep market research and competitor notes reusable
- Design MVPs and product concepts from real pain points
- Track business model assumptions before they become fake certainty
- Run validation experiments with explicit success criteria
- Let AI agents organize, question, and improve your founder thinking

## Who It Is For

- Solo founders exploring new startup ideas
- Product builders validating a market or MVP
- Indie hackers organizing customer problems and experiments
- Operators who want a lightweight alternative to heavy startup tooling
- AI-assisted founders who want a structured knowledge base for agents

## Folder Structure

```text
FounderOS/
├── 00-Inbox/            # Raw notes, quick captures, unfinished thoughts
├── 01-Ideas/            # Startup ideas, opportunities, hypotheses
├── 02-Problems/         # Customer problems, pain points, unmet needs
├── 03-Market/           # Market research, competitors, trends, categories
├── 04-Products/         # Product concepts, MVPs, user flows, product specs
├── 05-Business-Models/  # Pricing, channels, revenue models, unit economics
├── 06-Founder-Notes/    # Founder reflections, decisions, principles, reviews
├── 07-Experiments/      # Interviews, MVP tests, validation plans, results
├── 08-Resources/        # Articles, books, cases, tools, courses
├── templates/           # Reusable note templates
├── examples/            # Filled examples showing how to use the system
├── docs/                # Extra guides and project documentation
├── AGENTS.md            # AI agent collaboration instructions
└── README.md
```

## Quick Start

1. Clone or download this repository.
2. Open the folder in Obsidian, VS Code, Cursor, or any Markdown editor.
3. Put unprocessed thoughts in `00-Inbox/`.
4. Copy a template from `templates/` into the right folder.
5. Use `07-Experiments/` to turn important assumptions into validation work.

## Templates

FounderOS includes reusable templates:

| Template | Use it for |
| --- | --- |
| [idea.md](templates/idea.md) | Capturing a startup idea and its assumptions |
| [problem.md](templates/problem.md) | Describing a real customer problem |
| [market-research.md](templates/market-research.md) | Studying a market, category, or competitor landscape |
| [business-model.md](templates/business-model.md) | Thinking through pricing, channels, revenue, and unit economics |
| [experiment.md](templates/experiment.md) | Designing a validation experiment with success criteria |

## Example Workflow

See [examples/ai-study-planner](examples/ai-study-planner/) for a filled example.

The example shows how one idea moves through the system:

```text
AI Study Planner
├── idea.md
├── problem.md
├── market-research.md
├── business-model.md
└── experiment.md
```

This is the intended FounderOS rhythm: start with an idea, clarify the problem, understand the market, model the business, then test the riskiest assumption.

## Working With AI Agents

FounderOS is designed to be AI-friendly. The project-level agent instructions live in [AGENTS.md](AGENTS.md).

You can ask an AI assistant to:

- organize raw notes from `00-Inbox/`
- turn an idea into testable hypotheses
- extract customer problems from interview notes
- draft experiments with measurable success standards
- compare market research notes and identify open questions
- suggest the next smallest validation action

## Recommended Workflow

### 1. Capture

Put everything unfinished in `00-Inbox/` first. Do not over-organize early thoughts.

### 2. Clarify

Move notes into:

- `01-Ideas/` when it is a possible startup direction
- `02-Problems/` when it describes a real user pain
- `03-Market/` when it is about industry structure, competitors, or trends

### 3. Shape

Use:

- `04-Products/` for product concepts and MVPs
- `05-Business-Models/` for pricing, channels, and revenue logic

### 4. Validate

Use `07-Experiments/` to define the assumption, test method, success standard, result, and next decision.

### 5. Review

Use `06-Founder-Notes/` for founder reflections, weekly reviews, decision logs, and operating principles.

## Principles

1. Capture before organizing.
2. Keep original context when an idea is still uncertain.
3. Separate facts, judgments, and hypotheses.
4. Prefer evidence over confidence.
5. Every serious idea should eventually become an experiment.
6. Notes should help decisions, not become a private museum.

## Contributing

FounderOS is a Markdown knowledge system, so contributions are usually templates, examples, workflow notes, translations, or small wording improvements.

See [CONTRIBUTING.md](CONTRIBUTING.md) for details.

## License

MIT License. See [LICENSE](LICENSE).
