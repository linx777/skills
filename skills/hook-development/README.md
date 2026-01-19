# hook-development

Creates lifecycle hooks for plugins with strong validation and telemetry.

## Overview

Drafts pre- and post-command hooks, validates inputs, and wires telemetry for plugin systems. It ensures hooks are composable, typed, and easy to test before rolling into production.

## Metadata

- Author: Anthropic
- Downloads: 2.6k
- Stars: 56950
- Roles: DevOps
- Type: Agent Skill / Plugin Dev
- Last updated: 2025.11.17

## Compatibility

- Claude Code CLI
- Codex CLI
- Claude App
- Gemini CLI

## Setup

Command:

```bash
claude mcp add hook-development
```

YAML config:

```yaml
tools:
  - name: hook-development
    language: typescript
    hooks: [pre, post]
```

## Repository

https://github.com/anthropics/claude-code/tree/main/plugins/plugin-dev/skills/hook-development

## Included Files

- SKILL.md
- examples/
- references/
- scripts/

## Triggers

- Add a pre-execution hook to this plugin
- Validate inputs and outputs for this hook
- Instrument telemetry for plugin lifecycle events

## Features

- Generates hook scaffolds with typings and validation
- Includes telemetry and error-handling patterns
- Provides tests to cover hook behavior

## Best For

- Plugin developers adding lifecycle hooks
- Teams enforcing consistent validation
- Maintainers instrumenting plugin behavior

## Tags

- Hooks
- Plugins
- Telemetry
- Validation
- TypeScript
