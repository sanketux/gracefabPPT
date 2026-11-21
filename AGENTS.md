# AGENTS.md

Instructions for AI coding agents (Claude Code, Codex, Cursor, etc.) working in this repository.

## Project

**gracefabPPT**: the presentation deck for Gracefab.

## Repository layout

| Path | Purpose |
| --- | --- |
| `AGENTS.md` | This file. Rules and context for agents. |
| `context-files/` | Source material: brand guidelines, logos, product details, copy, data, notes. |

## Before you start

1. Read every file in `context-files/`. It is the source of truth for brand, tone, and facts.
2. Don't make up facts, figures, client names, or claims. If something is missing, ask or leave a clear `TODO` placeholder.

## Working rules

- Stick to the brand colors, fonts, and tone described in `context-files/`.
- Keep slides concise: one idea per slide, short headlines, minimal body text.
- Put new reference material in `context-files/`, not in the repo root.
- Use clear, lowercase, hyphenated file names (e.g. `brand-guidelines.pdf`).
- Don't commit secrets, credentials, or private client data.

## Git

- Work on a feature branch and open a pull request. Don't push directly to `main`.
- Write short, descriptive commit messages in the imperative mood.
