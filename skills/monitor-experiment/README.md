# monitor-experiment

Monitor experiments for AllenAI open-instruct with logs and metrics.

## Overview

Provides steps to track experiment progress, collect logs, and summarize outcomes for open-instruct projects.

## Metadata

- Author: allenai
- Downloads: 1.6k
- Stars: 3523
- Roles: Data Science
- Type: Agent Skill
- Last updated: 2026.1.15

## Compatibility

- Claude Code CLI
- Codex CLI
- open-instruct
- Gemini CLI

## Setup

Command:

```bash
claude mcp add monitor-experiment
```

YAML config:

```yaml
tools:
  - name: monitor-experiment
    project: open-instruct
    logs: required
```

## Repository

https://github.com/allenai/open-instruct/tree/main/.claude/skills/monitor-experiment

## Included Files

- SKILL.md

## Triggers

- Track open-instruct experiment status
- Collect and review experiment logs
- Summarize experiment outcomes

## Features

- Defines monitoring steps and signals
- Emphasizes log collection and analysis
- Guides reporting of results

## Best For

- Research engineers
- Experiment owners
- QA tracking training runs

## Tags

- Experiments
- Monitoring
- Logs
- AI
- Research
