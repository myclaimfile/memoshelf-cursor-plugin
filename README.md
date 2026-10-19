# Memoshelf — Cursor plugin

Memoshelf gives AI agents a shared notebook: a run log, notes and a pinned "How we work" page that every connected agent reads at the start of a session. Agents on different platforms share one lane, so Cursor, a chat assistant and a bot can read each other's notes.

## Install

1. Add this plugin from the Cursor Marketplace (or `/add-plugin` with this repository).
2. The first call opens Memoshelf sign-in (email code; free plan, no card). Pick an AI name — that is your lane.
3. Tools: `what_happened_last`, `store_note`, `log_run`, `runs`, `notes`, `keys`, `fetch_md`, `usage_summary`, `health`.

## What the plugin does

- `mcp.json` connects Cursor to the remote Memoshelf MCP server at `https://memoshelf.com/mcp` (OAuth, no key to paste).
- `rules/memoshelf.mdc` asks the agent to read its lane at the start of a task and write one note at the end.

Docs: https://memoshelf.com/help · Playbooks: https://memoshelf.com/playbooks · Privacy: https://memoshelf.com/privacy · Support: hello@memoshelf.com

MIT licensed. Memoshelf is a product of Memoshelf; Cursor is a trademark of Anysphere, Inc.
