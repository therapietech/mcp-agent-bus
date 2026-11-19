# Changelog

All notable changes to this project are documented here.  
Format loosely follows [Keep a Changelog](https://keepachangelog.com/en/1.1.0/).

**Deployments:** each section is one merge to [`main`](https://github.com/therapietech/mcp-agent-bus) (pull request = deployment).

## [Unreleased]

## [1.2.0] - 2026-11-12 — [#2](https://github.com/therapietech/mcp-agent-bus/pull/2)

### Added

- **Microsoft Teams notifications** (`TEAMS_WEBHOOK_URL`, `TEAMS_NOTIFY_EVENTS`).
- **`docs/teams-notify.md`**.

### Changed

- **`src/worker.mjs`** — Teams Adaptive Cards; **worker MCP safety** (`WORKER_FORCE` default off, allow-list required with force, global MCP startup warning).
- **`README.md`**, **`examples/mcp-agent-bus.mdc`**.

## [1.1.0] - 2026-10-06 — [#1](https://github.com/therapietech/mcp-agent-bus/pull/1)

### Changed

- **README** — CI status badge; roadmap wording for org release.

## [1.0.0] - 2026-10-01

### Added

- First public org release: MCP bus, mailbox core, setup script, Quick start **README**, monitoring dashboards (**`docs/watch-*.sh`**) and worker metrics (aligned with personal **v1.1.0** snapshot).

[1.2.0]: https://github.com/therapietech/mcp-agent-bus/releases/tag/v1.2.0
[1.1.0]: https://github.com/therapietech/mcp-agent-bus/releases/tag/v1.1.0
[1.0.0]: https://github.com/therapietech/mcp-agent-bus/releases/tag/v1.0.0