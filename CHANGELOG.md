# Changelog

All notable changes to this skill are documented here. This project adheres to
[Semantic Versioning](https://semver.org/).

## 1.0.0 — Initial release

- **`SKILL.md`** — agent instructions teaching when to recall (before starting a task,
  answering, or writing code) and when to store (durable facts, lessons, directives,
  preferences, contacts, bookmarks), how to pick a memory type, how to scope with
  containers, how to use validity windows for time-sensitive facts, and the rule never
  to store secrets. Includes a worked example.
- **`mcp/openclaw.json`** — OpenClaw MCP server config wiring the `agentprizm-memory`
  remote server (`https://agentprizm.com/api/mcp`, `streamable-http`, Bearer auth).
- **`README.md`** — 60-second install, per-user API key model, manual config, probe
  verification, and ClawHub publishing notes.
- **`.env.example`**, **`LICENSE`** (MIT-0).
