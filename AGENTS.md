# AGENTS.md — The Bet Tree

Instructions for coding and chat agents working in this repository.
Human quick start stays in [README.md](README.md). Full skill workflow: [skills/bet-tree/SKILL.md](skills/bet-tree/SKILL.md).

## What this repo is

A public method for weekly bets under uncertainty. Blanks live in `templates/`. Session scripts live in `prompts/`. Do not invent private company data or metrics.

## Hard rules

1. Ask one question, then wait.
2. Never invent numbers. Write **unknown**.
3. Do not dump `docs/method.md` as a wall of text.
4. Write filled blanks only to paths the user names. Keep PII out of this public repo.
5. Monday morning: one of four outcomes, then plan seven days. Friday morning: mid-check only, no outcome.
6. Basic blanks before Advanced (02–04, 06).
7. Several subprojects under one long bet: `prompts/portfolio.md` and template 09 before a single week sheet.

## Routing

| Situation | Start |
| --- | --- |
| One focus | `prompts/basic-cycle.md` section 1 |
| Which project is main | `prompts/portfolio.md` + `templates/09-portfolio-cycle-map.md` |
| Nested board under long bet | `templates/10-subproject-checklist.md` |
| After one lived basic week | `prompts/advanced.md` on the main line only |

## Tool adapters (thin)

| Agent | File |
| --- | --- |
| Any AGENTS.md-native tool | this file |
| Claude Code | [CLAUDE.md](CLAUDE.md) |
| GitHub Copilot | [.github/copilot-instructions.md](.github/copilot-instructions.md) |
| Gemini CLI | [GEMINI.md](GEMINI.md) |
| Cursor skill path | [.cursor/skills/bet-tree](.cursor/skills/bet-tree) → `skills/bet-tree` |
| Claude skill path | [.claude/skills/bet-tree](.claude/skills/bet-tree) → `skills/bet-tree` |
| Codex-style skill path | [.agents/skills/bet-tree](.agents/skills/bet-tree) → `skills/bet-tree` |

Paste-only chat (no skill loader): attach this file or paste one section from `prompts/`.

## Do not

- Edit circulated freeze briefs (not in this repo).
- Copy HQ product codenames or career paths into templates or examples.
- Require portfolio blanks in the human Start here path.
