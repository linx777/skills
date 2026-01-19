# connect

Connects external apps and services with unified auth flows.

## Overview

Provides a guided flow to connect third-party apps, configure credentials, and validate access so automations can run reliably.

## Metadata

- Author: sujayjayjay
- Downloads: 6.8k
- Stars: 21251
- Roles: DevOps
- Type: Agent Skill
- Last updated: 2026.1.11

## Compatibility

- Claude Code CLI
- Codex CLI
- Claude App
- Gemini CLI

## Setup

Command:

```bash
claude mcp add connect
```

YAML config:

```yaml
tools:
  - name: connect
    auth: oauth
    validate: true
```

## Repository

https://github.com/ComposioHQ/awesome-claude-skills/tree/master/connect

## Included Files

- LICENSE.txt
- SKILL.md

## Triggers

- Connect this app and validate access
- Set up OAuth for a new service
- Verify integration credentials for a workflow

## Features

- Guided auth setup with validation steps
- Credential storage and verification hints
- Connection health checks for workflows

## Best For

- Teams wiring external integrations
- Ops engineers configuring automations
- Builders validating app connections

## Tags

- Integrations
- OAuth
- Credentials
- Automation
- DevOps
