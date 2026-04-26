# Workflow

This repo covers the dashboard-specific workflow for The Depth's operational surface.

## Canonical flow
1. a dashboard need, bug, or improvement is identified
2. the work is linked to a GitHub issue when durable/non-trivial
3. the relevant data source or UI change is implemented in this repo
4. changes are reviewed against the issue's acceptance criteria
5. Homer validates QA when behavior changes
6. Tony performs UAT when needed
7. shipped behavior and durable lessons are reflected in repo docs/issues

## Repo usage
### Use this repo for
- dashboard UI and behavior
- local data files used by the dashboard
- documentation about dashboard purpose, workflow, and architecture
- dashboard-specific QA and iteration notes

### Do not use this repo for
- cross-project HQ workflow rules that belong in `depth-ops`
- unrelated product experiments
- chat-only status that should instead live in GitHub issues/PRs

## Delivery expectations
- meaningful changes should link back to an issue
- product/behavior changes should include validation notes in the PR
- docs should be kept current when the dashboard's shape or operating expectations change
