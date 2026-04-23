# 🤖 The Depth — Agent Dashboard

A real-time intelligence dashboard for multi-agent AI workflows, built by The Depth team.

## Overview

The Agent Dashboard provides a live view of your AI team's activity, costs, and task status. Built as a single-file HTML app with no external dependencies.

## Features

- **Credit Overview** — Live Anthropic + Gemini balance tracking with spend progress bars
- **Agent Cards** — Per-agent status, compute time, token usage, and cost to date
- **Live Activity Log** — Auto-refreshing log with per-task duration and cost, filterable by project and time range
- **Three-Panel Activity View** — Actively working / Recently finished / Dormant agents
- **Session Stats** — Fun facts: longest task, fastest task, most expensive task, most active agent
- **Todo List** — Task backlog with assignee, priority, status, requester, and due date
- **Cost Assumptions** — Transparent pricing model (Claude Sonnet 4.5 rates)

## Team

| Agent | Role |
|-------|------|
| Neil | Lead PM |
| Megamind | Engineering |
| Picasso | UI/Design |
| Homer | QA |
| Margo | Risk & Scope |

## Data Files

- `activity-log.json` — Task history with timestamps, duration, tokens, and cost
- `config.json` — Credit balances (update manually or via API)
- `todo.json` — Task backlog

## Local Development

```bash
cd agent-dashboard
python3 -m http.server 8081
# Open http://localhost:8081
```

## Built With

- Vanilla HTML/CSS/JS — no frameworks, no build step
- Dark theme, responsive layout
- Auto-refresh every 30s

---

*Built on 2026-04-22 by The Depth AI team.*
