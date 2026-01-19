# raffle-winner-picker

Selects raffle winners fairly with reproducible randomness.

## Overview

Runs a transparent raffle draw with seedable randomness, tie-break rules, and audit-friendly output.

## Metadata

- Author: Prathit-tech
- Downloads: 6.8k
- Stars: 21251
- Roles: Product Management
- Type: Agent Skill
- Last updated: 2025.10.17

## Compatibility

- Claude App
- Codex CLI
- Claude Code CLI
- Gemini CLI

## Setup

Command:

```bash
claude mcp add raffle-winner-picker
```

YAML config:

```yaml
tools:
  - name: raffle-winner-picker
    seed: required
    winners: 1
```

## Repository

https://github.com/ComposioHQ/awesome-claude-skills/tree/master/raffle-winner-picker

## Included Files

- LICENSE.txt
- SKILL.md

## Triggers

- Pick a random winner from this list
- Run a raffle with a fixed seed
- Select multiple winners and alternates

## Features

- Uses seedable randomness for auditability
- Supports multiple winners and alternates
- Outputs a clear draw log

## Best For

- Community giveaways
- Event organizers
- Teams running internal raffles

## Tags

- Raffle
- Random
- Fairness
- Events
- Utilities
