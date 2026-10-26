# Using Bet Tree with an assistant

Three short steps.

1. Clone or open [nareyko/bet-tree](https://github.com/nareyko/bet-tree). Give the assistant read access to this folder.
2. Point it at [`.cursor/skills/bet-tree/SKILL.md`](../.cursor/skills/bet-tree/SKILL.md) or paste the matching block from [`prompts/`](../prompts/).
3. Answer one question at a time. Copy blanks from [`templates/`](../templates/) into your own notes. Keep private names out of this public repo.

The assistant should ask, wait, and fill blanks. It should not invent numbers. Missing facts stay **unknown**.

One project: start [`prompts/basic-cycle.md`](../prompts/basic-cycle.md).  
Several subprojects under one long bet: start [`prompts/portfolio.md`](../prompts/portfolio.md), then blanks 09 and 10.  
After one lived basic week: [`prompts/advanced.md`](../prompts/advanced.md).

Tool surface (what counts as "tools" without a custom server): [`mcp-surface.md`](mcp-surface.md).
