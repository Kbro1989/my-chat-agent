# my-chat-agent — Scheduled Task Agent (Fork)

> TypeScript · Cloudflare Agents SDK · AIChatAgent · Fork

Fork of [pick-of-gods/my-chat-agent](https://github.com/pick-of-gods/my-chat-agent).
`AIChatAgent` with scheduled tasks, human-in-the-loop tool confirmation, and MCP integration.

## Tools

| Tool | Auto | Purpose |
|---|---|---|
| `getWeatherInformation` | ❌ | Requires user confirmation |
| `getLocalTime` | ✅ | Local time lookup |
| `scheduleTask` | ✅ | cron / delay / datetime scheduling |
| `getScheduledTasks` | ✅ | List scheduled tasks |
| `cancelScheduledTask` | ✅ | Cancel by ID |

Model: `gpt-4o-2024-11-20`

```
src/server.ts   # AIChatAgent + scheduled task handler
src/tools.ts    # Zod-validated tool definitions
```
