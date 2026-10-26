# Using Bet Tree with an assistant

Three short steps.

1. Clone or open [nareyko/bet-tree](https://github.com/nareyko/bet-tree). Give the assistant read access to this folder.
2. Point it at [AGENTS.md](../AGENTS.md) or [skills/bet-tree/SKILL.md](../skills/bet-tree/SKILL.md). If the tool has no skill loader, paste one section from [`prompts/`](../prompts/).
3. Answer one question at a time. Copy blanks from [`templates/`](../templates/) into your own notes. Keep private names out of this public repo.

The assistant should ask, wait, and fill blanks. It should not invent numbers. Missing facts stay **unknown**.

One project: start [`prompts/basic-cycle.md`](../prompts/basic-cycle.md).  
Several subprojects under one long bet: start [`prompts/portfolio.md`](../prompts/portfolio.md), then blanks 09 and 10.  
After one lived basic week: [`prompts/advanced.md`](../prompts/advanced.md).

## Which file for which agent

| Agent | Open |
| --- | --- |
| Cursor | [AGENTS.md](../AGENTS.md); skill at [.cursor/skills/bet-tree](../.cursor/skills/bet-tree) (symlink to canon) |
| Claude Code | [CLAUDE.md](../CLAUDE.md) and [.claude/skills/bet-tree](../.claude/skills/bet-tree) |
| GitHub Copilot | [.github/copilot-instructions.md](../.github/copilot-instructions.md) |
| Gemini CLI | [GEMINI.md](../GEMINI.md) |
| Codex and other AGENTS.md tools | [AGENTS.md](../AGENTS.md); optional [.agents/skills/bet-tree](../.agents/skills/bet-tree) |
| Chat paste only | Attach `AGENTS.md` or one block from `prompts/` |

Canon skill (edit once): [`skills/bet-tree/SKILL.md`](../skills/bet-tree/SKILL.md).

Tool surface (what counts as "tools" without a custom server): [`mcp-surface.md`](mcp-surface.md).
