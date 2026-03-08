# RuleForge — Free AGENTS.md Prompt Generator

```
┌──────────────────────────────────────────────────────────┐
│                                                          │
│   Rule ████████                                          │
│        Forge                                             │
│                                                          │
│   AI AGENT CONFIG GENERATOR                              │
│   One form. Every agent config.                          │
│                                                          │
│   ▸ INITIALIZE                                           │
│                                                          │
│   v1.0.0 — Sorted. Tools                                 │
│                                                          │
└──────────────────────────────────────────────────────────┘
```

**Stop copy-pasting AGENTS.md templates. Start forging them.**

RuleForge generates structured prompts that tell your AI coding tool exactly how to build a project-specific `AGENTS.md` file — optimized for your stack, your commands, your architecture.

You fill out a form. You get a prompt. You paste it into Claude, Cursor, Copilot, or any AI tool. It generates your `AGENTS.md`. Done.

---

## ▸ [Launch RuleForge](https://yumakakuya.github.io/sorted-ruleforge/)

---

## What is AGENTS.md?

`AGENTS.md` is the open standard for AI coding agent instructions, backed by Google, OpenAI, Cursor, and Sourcegraph. It tells AI tools how your project works — build commands, code style, testing, architecture, security — so they stop guessing and start following your rules.

Think of it as `README.md` for humans, `AGENTS.md` for AI agents.

The problem: most developers know they need one, but writing it from scratch is tedious. Templates are too generic. `/init` generates bloat you have to delete.

RuleForge solves this by generating a **prompt** — not a template — that produces a project-specific `AGENTS.md` tailored to your exact setup.

## How It Works

```
┌─────────────┐     ┌─────────────┐     ┌─────────────┐
│  FILL FORM  │ ──▸ │ GET PROMPT  │ ──▸ │  PASTE INTO  │
│             │     │             │     │  AI TOOL     │
│ Project     │     │ Structured  │     │              │
│ Tech Stack  │     │ instructions│     │ Claude Code  │
│ Commands    │     │ for your AI │     │ Cursor       │
│ Style       │     │ coding tool │     │ Copilot      │
│ Architecture│     │             │     │ Windsurf     │
│ Boundaries  │     │             │     │ Cline        │
└─────────────┘     └─────────────┘     └─────────────┘
                                              │
                                              ▾
                                     ┌─────────────┐
                                     │ AGENTS.md   │
                                     │ generated   │
                                     │ for YOUR    │
                                     │ project     │
                                     └─────────────┘
```

**1. Fill the form** — Project name, tech stack, commands, code style, architecture rules, protected files, forbidden actions.

**2. Copy the prompt** — RuleForge generates a structured prompt with all your project context baked in.

**3. Paste into your AI tool** — Claude Code, Cursor, GitHub Copilot, Windsurf, Cline, Codex — any tool that accepts markdown prompts.

**4. Get your AGENTS.md** — The AI generates a project-specific config file, not a generic template.

## Why a Prompt, Not a Template?

Templates don't know your project. They give you boilerplate that you spend 30 minutes editing.

`/init` commands scan your repo but generate bloat — "yes, Claude, this is a TypeScript project, I can see that from the package.json."

RuleForge takes a different approach: **it generates instructions for the AI, not the file itself.** The AI then reads your actual codebase and produces an `AGENTS.md` that fits. Your context + AI's code awareness = config files that actually work.

## What the Form Covers

| Section | What You Specify |
|---|---|
| **Project Identity** | Name, description, purpose, monorepo structure |
| **Tech Stack** | Languages, frameworks, databases, package manager, deployment targets |
| **Commands** | Dev, build, test, lint, deploy, type check, custom commands |
| **Verification** | What to run after every change |
| **Code Style** | Module system, exports, indentation, naming, commit format, linters, test frameworks |
| **Architecture** | Directory structure, protected files, architectural rules, gotchas |
| **Boundaries** | AI permissions, forbidden actions |
| **Cross-tool** | Which AI tools should be compatible |

## Supported AI Tools

RuleForge generates prompts compatible with:

- **Claude Code** — Anthropic's terminal-based coding agent
- **Cursor** — AI-native code editor
- **GitHub Copilot** — GitHub's AI coding assistant
- **Windsurf** — Codeium's AI editor
- **Cline** — Open-source autonomous coding agent
- **Codex** — OpenAI's coding agent

All from the same prompt. `AGENTS.md` is tool-agnostic by design.

## Example Output

Here's what a generated prompt looks like (abbreviated):

```
## ROLE
You are an expert AI development environment architect.
Generate a AGENTS.md file for the following project.

## PROJECT CONTEXT
- Name: ShopFront
- Description: Next.js e-commerce app with Stripe payments and Prisma ORM

## TECH STACK
- Language: TypeScript
- Framework: Next.js
- Database: PostgreSQL, Prisma
- Package Manager: pnpm

## COMMANDS
- Dev: `pnpm dev`
- Build: `pnpm build`
- Test: `pnpm test`

## ARCHITECTURE
### Protected Files (NEVER modify)
.env, prisma/schema.prisma

## AGENTS.md SPECIFIC REQUIREMENTS
- This file must be tool-agnostic
- Follow the AGENTS.md open standard format
- Do NOT include tool-specific syntax

## OUTPUT REQUIREMENTS
- Output ONLY the raw markdown content
- Keep total length under 150 lines
- Every line must earn its place
```

You paste this into Claude, Cursor, or any AI tool. It reads your codebase and generates the actual `AGENTS.md`.

## Tech

- Pure HTML/CSS/JS — single file, no dependencies
- Zero API calls — runs entirely in your browser
- No data collection — your project info never leaves your machine
- Works offline after first load

## Full Version

This free version generates `AGENTS.md` prompts only.

**[RuleForge Full](https://sorted.tools)** ($9.99, one-time) adds:

- `CLAUDE.md` — Claude Code project memory with file hierarchy, progressive disclosure, @import support
- `.cursorrules / .mdc` — Cursor rules with glob scoping and YAML frontmatter
- `SKILL.md` — Dynamic agent skills with hooks and trigger commands
- **Multi-format export** — Fill the form once, generate all 4 formats simultaneously
- **Cross-format sync** — Symlink setup commands for keeping all configs in sync

One form. Four formats. Every AI coding tool configured.

## About

Built by **[@null_founder](https://x.com/null_founder)** — indie dev building tools for developers who ship.

Part of the **[Sorted. Tools](https://github.com/yumakakuya)** ecosystem.

---

```
© 2026 Sorted. Tools — RuleForge Series
```
