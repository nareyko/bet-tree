# MCP and tool surface (v1)

Bet Tree v1 does **not** ship a custom MCP server binary. An agent with filesystem (or git) access to this repository is enough.

## Resources (read)

| Path | Role |
| --- | --- |
| `prompts/*.md` | Scripts the agent follows |
| `templates/01-bet.md` … `08-meeting.md` | Basic and advanced blanks |
| `templates/09-portfolio-cycle-map.md` | Multi-subproject cycle roles |
| `templates/10-subproject-checklist.md` | Nested board under the long bet |
| `templates/print-sheets.html` | Printable basic set |
| `.cursor/skills/bet-tree/SKILL.md` | Routing and hard rules |
| `docs/method.md` | Reference only; do not dump whole file |

## Tools (write)

| Action | Rule |
| --- | --- |
| Create or update a blank copy | Only on a path the user names (their notes, not canon templates with PII) |
| Edit canon under `templates/` or `docs/` | Only when the user is maintaining the method itself |
| Invent metrics into any file | Forbidden; write `unknown` |

## Optional v2

If clients need a formal MCP server later, expose the same paths as resources and the same write rules as tools. Do not add network calls or private HQ data.
