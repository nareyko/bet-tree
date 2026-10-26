---
name: bet-tree
description: >-
  Runs The Bet Tree weekly cycle with a founder: one question at a time, blank
  sheets, unknown for missing numbers. Use when the user mentions Bet Tree,
  weekly bets, Monday or Friday ritual, L-frame, guardrails, or several
  subprojects under one long Founder or Business bet.
---

# Bet Tree (agent skill)

## Hard rules

1. Ask **one** question, then wait. Do not stack a questionnaire.
2. Never invent customers, quotes, money, percentages, sample sizes, or thresholds. Write **unknown**.
3. Do not paste `docs/method.md` as a wall of text. Point to one short section or one blank only when needed.
4. Prefer artifacts: filled blanks under paths the user confirms. Do not put private names into this public repo.
5. Calendar: Monday morning judges the past week (one of four outcomes) then plans seven days. Friday morning is a mid-week check only, with no outcome.
6. Basic before Advanced. Do not open templates 02–04 or 06 until one basic week has been lived.
7. If the user has several living subprojects under one 3–5 year stake, run `prompts/portfolio.md` and template `09` before a single week sheet.

## File map

| Need | Open |
| --- | --- |
| Basic week | `templates/01-bet.md`, `05-week.md`, `07-journal.md`, `08-meeting.md` |
| Printable basic set | `templates/print-sheets.html` |
| Portfolio roles | `templates/09-portfolio-cycle-map.md` |
| Nested subproject tree | `templates/10-subproject-checklist.md` |
| Prompt scripts | `prompts/basic-cycle.md`, `prompts/portfolio.md`, `prompts/advanced.md` |
| How to wire an agent | `docs/agent.md`, `docs/mcp-surface.md` |

## Routing

1. New founder, one focus: start `prompts/basic-cycle.md` from section 1.
2. "Which of my projects is main?" or three workstreams: start `prompts/portfolio.md` and blank 09.
3. Subproject needs its own board under the long bet: use blank 10; still one Monday and one Friday for the portfolio.
4. After one lived basic week: use `prompts/advanced.md` only for the main line (or the subproject that owns the Monday slot).

## Portfolio and dashboard patterns (no private data)

Encode practice as empty structure only:

- Exactly one **main** subproject per cycle; parallel and background stay visible.
- Background must not steal the Monday slot; keep a small attention quota and a stop list.
- A noisy project is not automatically the constraint. Ask which line blocks the long bet.
- Numbers live in a named SoT (status file, notebook). A cycle dashboard is an overview; it is not a second source of truth for metrics.

## First reply pattern

When the user says "run Bet Tree" or drops this repo:

1. Confirm: one project or several under one long bet.
2. Start the matching prompt at its first question only.
3. Offer to copy the matching blank into a path they name.
