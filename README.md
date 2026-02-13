# RemoteCTO Claude Code Plugins

Plugin marketplace for Claude Code.

## Install

```bash
/plugin marketplace add RemoteCTO/claude-plugins-marketplace
```

## Available plugins

| Plugin | Description | Repo |
|--------|-------------|------|
| `timelog` | Automatic time tracking | [claude-code-timelog](https://github.com/RemoteCTO/claude-code-timelog) |
| `seamless-claude` | Zero-downtime compaction | [seamless-claude](https://github.com/RemoteCTO/seamless-claude) |

### timelog

Logs session activity (prompts, projects, tickets)
as JSONL for timesheet reconstruction. Includes
`claudelog` CLI for reports and backfill.

```bash
/plugin install timelog
```

### seamless-claude

Eliminates compaction downtime. Monitors context
usage, fires background compaction early, and
auto-resumes fresh sessions from the prepared
summary. Includes `claude-resume` CLI for
cross-session resume.

```bash
/plugin install seamless-claude
```
