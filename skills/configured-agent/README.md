# configured-agent

Produces plugin settings templates and configuration docs for agents.

## Overview

Defines configurable knobs for agents - tool access, safety thresholds, routing rules - and generates clear documentation for operators. It standardizes how teams ship configurable agent experiences.

## Metadata

- Author: Anthropic
- Downloads: 3.1k
- Stars: 56950
- Roles: Product Management
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
claude mcp add configured-agent
```

YAML config:

```yaml
tools:
  - name: configured-agent
    presets: true
    safety: configurable
```

## Repository

https://github.com/anthropics/claude-code/tree/main/plugins/plugin-dev/skills/plugin-settings

## Included Files

- SKILL.md
- examples/
- references/
- scripts/

## Triggers

- Add configurable settings to this agent
- Document presets and safety modes for operators
- Draft a config guide for plugin deployment

## Features

- Creates settings schemas with defaults and fallbacks
- Documents configuration modes for operators
- Pairs presets with safety and observability notes

## Best For

- Teams shipping configurable agents
- Platform operators managing plugin settings
- Maintainers standardizing agent presets

## Tags

- Agents
- Configuration
- Safety
- Docs
- Presets
