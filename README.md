# FounderOS

FounderOS is an open, Markdown-first operating system for founders to capture ideas, study markets, clarify customer problems, design products, and turn assumptions into experiments.

Chinese version: `README.zh-CN.md`.

It is built for people who think with notes and want an AI-friendly workspace that keeps startup thinking grounded in evidence, not just inspiration.

## Who It Is For

- Solo founders exploring new startup ideas
- Product builders validating a market or MVP
- Indie hackers organizing customer problems and experiments
- Operators who want a lightweight alternative to heavy startup tooling
- AI-assisted founders who want a structured knowledge base for agents

## Core Idea

Most startup notes get lost because they mix five different things:

- raw ideas
- real customer problems
- market observations
- product concepts
- validation evidence

FounderOS separates them so each thought can move forward:

```text
idea -> problem -> market -> product -> business model -> experiment -> decision
```

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
2. Open the `FounderOS/` folder in Obsidian, VS Code, Cursor, or any Markdown editor.
3. Put unprocessed thoughts in `00-Inbox/`.
4. When an idea becomes clearer, move it into the right folder using a template from `templates/`.
5. Use `07-Experiments/` to turn assumptions into concrete validation work.

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

Use `07-Experiments/` to define:

- the assumption being tested
- the test method
- the success standard
- the result
- the next decision

### 5. Review

Use `06-Founder-Notes/` for founder reflections, weekly reviews, decision logs, and operating principles.

## Templates

Start from these files:

- `templates/idea.md`
- `templates/problem.md`
- `templates/experiment.md`
- `templates/market-research.md`
- `templates/business-model.md`

Copy a template into the right folder, rename it, and fill it out.

## Example

See `examples/ai-study-planner/` for a filled example of how one idea moves through the system:

- idea
- user problem
- market research
- business model
- validation experiment

## Working With AI Agents

FounderOS is designed to be easy for AI agents to understand. The project-level agent instructions live in `AGENTS.md`.

When using an AI assistant, you can ask it to:

- organize raw notes from `00-Inbox/`
- turn an idea into testable hypotheses
- extract customer problems from interview notes
- draft experiments with measurable success standards
- compare market research notes and identify open questions

## Principles

1. Capture before organizing.
2. Keep original context when an idea is still uncertain.
3. Separate facts, judgments, and hypotheses.
4. Prefer evidence over confidence.
5. Every serious idea should eventually become an experiment.
6. Notes should help decisions, not become a private museum.

## Contributing

Contributions are welcome. Useful contributions include:

- better templates
- stronger examples
- founder workflows
- AI agent instructions
- translations
- Obsidian-specific improvements

See `CONTRIBUTING.md` for details.

## License

MIT License. See `LICENSE`.
