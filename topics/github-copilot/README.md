# 🤖 GitHub Copilot

Master GitHub Copilot as your AI pair programmer and productivity multiplier.

## 🎯 Learning Goals

- [ ] Understand how GitHub Copilot works and what it can (and can't) do
- [ ] Use Copilot Chat effectively for explanations, generation, and debugging
- [ ] Write effective prompts and inline comments to guide suggestions
- [ ] Use prompt files (`.prompt.md`) to create reusable AI workflows
- [ ] Leverage Copilot for code reviews, test generation, and documentation
- [ ] Build agentic workflows with Copilot in VS Code
- [ ] Understand Copilot's context window and how to optimise it
- [ ] Use `copilot-instructions.md` to customise Copilot behaviour per repository

## 🗺️ Learning Path

### Stage 1: Foundations
- How Copilot works (LLMs, tokens, context)
- Setting up Copilot in VS Code
- Inline completions — accepting, cycling, and guiding suggestions
- Copilot Chat basics — ask, explain, fix, generate

### Stage 2: Effective Prompting
- Writing clear inline comments to steer completions
- Prompt engineering fundamentals for code generation
- Using `/explain`, `/fix`, `/tests`, `/doc` slash commands
- Context management — what Copilot can see

### Stage 3: Prompt Files & Customisation
- Creating `.prompt.md` files for reusable prompts
- Using variables (`${variable}`) in prompts
- Setting up `copilot-instructions.md` for repository context
- Topic-specific mentor agents

### Stage 4: Advanced & Agentic Workflows
- Multi-step agentic tasks in Copilot
- Using Copilot for refactoring and code review
- Generating tests and documentation at scale
- Integrating Copilot into your daily development workflow

## 📁 Folder Structure

```
topics/github-copilot/
├── notes/       ← Add your markdown notes here
├── exercises/   ← Practice exercises and experiments
└── README.md    ← This file
```

## 🔗 Related Topics

- **Dev Principles & Practices** — Copilot works best when you know what *good* code looks like
- **Architecture** — Use Copilot to explore design patterns and architectural decisions

## 🤖 Mentor

Use the general `@mentor` prompt with `topic = "GitHub Copilot"`, or simply chat with Copilot directly in this repository — it already has context from `.github/copilot-instructions.md`.
