# kimi-cli-help

Answer Kimi CLI usage, configuration, and troubleshooting questions.

## Overview

Points to official docs, source navigation, and topic maps (install, config, providers, env vars, slash commands, shortcuts, MCP, agents) to resolve Kimi CLI issues quickly.

## Metadata

- Author: MoonshotAI
- Downloads: 2.4k
- Stars: 3855
- Roles: Product Management
- Type: Agent Skill
- Last updated: 2026.1.9

## Compatibility

- Kimi CLI
- Claude Code CLI
- Codex CLI
- Gemini CLI

## Setup

Command:

```bash
claude mcp add kimi-cli-help
```

YAML config:

```yaml
tools:
  - name: kimi-cli-help
    docs: https://moonshotai.github.io/kimi-cli
    source: https://github.com/MoonshotAI/kimi-cli
```

## Repository

https://github.com/MoonshotAI/kimi-cli/tree/main/src/kimi_cli/skills/kimi-cli-help

## Included Files

- SKILL.md

## Triggers

- Answer questions about Kimi CLI installation or configuration
- User asks about slash commands, shortcuts, providers, or env vars
- Need to reference Kimi CLI docs or source for troubleshooting

## Features

- Links documentation index and topic-specific pages (config, providers, commands)
- Outlines when to read local/source vs docs
- Includes guidance on MCP, agents, and internal architecture queries

## Best For

- Kimi CLI users needing help
- Contributors debugging Kimi CLI behavior
- Support teams answering configuration questions

## Tags

- Kimi
- CLI
- Docs
- Support
- Troubleshooting
