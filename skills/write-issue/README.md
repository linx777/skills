# write-issue

Writing and maintaining GitHub issues for the tldraw repository.

## Overview

Sets title standards, issue types and labels, body expectations for bugs/features/examples, and triage workflows for new or stale issues.

## Metadata

- Author: tldraw
- Downloads: 2.2k
- Stars: 44585
- Roles: Product Management
- Type: Agent Skill
- Last updated: 2026.1.6

## Compatibility

- Claude App
- Codex CLI
- Claude Code CLI
- tldraw
- GitHub
- Gemini CLI

## Setup

Command:

```bash
claude mcp add write-issue
```

YAML config:

```yaml
tools:
  - name: write-issue
    platform: github
    assets: optional
```

## Repository

https://github.com/tldraw/tldraw/tree/main/.claude/skills/write-issue

## Included Files

- SKILL.md

## Triggers

- Create or edit issues in tldraw/tldraw
- Clean up titles, types, or labels for triage
- Document reproduction steps or feature requests

## Features

- Defines title rules and issue types/labels
- Provides bug/feature/example body expectations
- Covers triage workflow for new or stale issues

## Best For

- tldraw maintainers triaging backlog
- Contributors filing clear issues
- Community managers cleaning metadata

## Tags

- Issues
- GitHub
- tldraw
- Triage
- Docs
