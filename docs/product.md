# Product

## Purpose
`agent-dashboard` is The Depth's operational dashboard for monitoring multi-agent work.

It exists to make team state legible at a glance: who is active, what work is moving, what it costs, and what still needs attention.

## Primary users
- Tony, as the primary operator and reviewer
- Neil, as orchestration lead tracking delivery state
- the rest of The Depth, as contributors aligning around shared status

## Jobs to be done
- show active, recent, and dormant agent work
- surface task backlog and ownership clearly
- make credit/cost usage visible
- provide a fast operational view without requiring several separate tools

## Current priorities
- keep credits accuracy reliable
- keep agent/task state easy to scan
- preserve a lightweight, dependency-free deployment model
- document the workflow so future agents can bootstrap into the repo cleanly

## Non-goals
- replacing GitHub as the durable source of truth for issues/PRs
- becoming a heavy web app with a complex build stack unless the product truly needs it
- hiding operational data behind opaque abstractions
