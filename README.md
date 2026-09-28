# Minz.ai for Claude

Skills that turn your Minz.ai workspace data into ready-to-use briefs: call preparation, pipeline reviews, a weekly plan and expense check-ins. The plugin connects Claude to the Minz.ai connector at `https://mcp.minz.ai/mcp`; you sign in with your Minz.ai account and choose which workspace to connect.

## Skills

| Skill | Use it to |
|---|---|
| `call-prep` | Prepare for a call or meeting with a customer: company, contacts, open deals, recent history and activities |
| `pipeline-review` | Review the sales pipeline: totals by stage, deals closing soon, deals that need attention |
| `my-week` | See your meetings, overdue and upcoming tasks and recent activities for a day or week |
| `expense-review` | Check your MinzSpend expenses and expense reports: what is pending, approved or reimbursed |

## What the plugin does and does not do

- **Read-only.** Every Minz.ai tool the skills use only reads data. Nothing is created, changed or deleted.
- **Your permissions.** Results follow your Minz.ai workspace membership, sharing rules and Spend permissions.
- **One destination.** The plugin talks only to `https://mcp.minz.ai/mcp`, over OAuth. It runs no scripts or hooks, installs no packages and sends data nowhere else.
- **No stored conversations.** Minz.ai receives only the lookup requests Claude sends to the connector, not your conversation.

## Setup

Install the plugin, then connect when Claude asks you to sign in to Minz.ai. If you belong to several workspaces, pick the one to use on the consent screen. Full guide: <https://mcp.minz.ai/docs>.

## Support

Email support@minz.ai. Privacy policy: <https://minz.ai/privacy>.
