# Architecture

## Current structure
The dashboard is intentionally lightweight:
- `index.html` contains the UI, styling, and client-side behavior
- `config.json` stores credit balance/configuration data
- `activity-log.json` stores activity history displayed in the UI
- `todo.json` stores the visible task backlog

## Runtime model
- static single-page app
- no build step
- served locally with a simple static file server or via GitHub Pages

## Design intent
The architecture favors:
- low friction edits
- easy inspection by humans and agents
- fast local iteration
- minimal operational dependency surface

## Key tradeoff
This simplicity makes the repo easy to bootstrap into, but it also means data contracts and UI logic live close together. If complexity grows materially, the repo may eventually need clearer module boundaries or a light build system.

## Dependencies
- modern browser runtime
- JSON data files kept in sync with the intended dashboard state
- GitHub Pages or a simple static server for hosting/viewing
