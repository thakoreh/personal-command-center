# Hiren OS — Personal Command Center

A local-first personal command center/dashboard prototype inspired by:

- Jerad Hill — `How I Manage My Entire Life with a Custom App I Built in Claude Code`
- Taelo Kim — `I Built a Command Center that Runs My Entire Life`

## Working modules

- Cockpit: open loops, project momentum, habit consistency, achievement assets
- Universal capture: task / idea / note / decision / agent routing
- Projects: progress tracking and next-action editing
- AI Agents: local simulated agent routing + copyable Hermes prompt
- Decisions: deterministic option scoring matrix
- Learning vault: video synthesis and knowledge notes
- Vision: flywheel, habit heatmap, achievement tracking, north-star graph
- Integrations: calendar/GitHub/Obsidian/Hermes/analytics status plus import/export JSON

## Data model

The app is static and local-first. All data persists in `localStorage` under `hiren-os-v1`. Use **Export data** to download a JSON backup.

## Future production integration path

1. Hermes Gateway for real agent tasks, inbox, and cron summaries.
2. Google Calendar read/write for day plans and time blocks.
3. Obsidian/local markdown indexing for knowledge vault.
4. GitHub/Coolify/deploy status for project receipts.
5. Analytics/Stripe/GA for revenue and growth dashboards.
