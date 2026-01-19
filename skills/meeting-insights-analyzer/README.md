# meeting-insights-analyzer

Summarizes meetings with decisions, risks, and action items.

## Overview

Transforms meeting notes or transcripts into structured summaries with decisions, owners, and next steps.

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
claude mcp add meeting-insights-analyzer
```

YAML config:

```yaml
tools:
  - name: meeting-insights-analyzer
    output: summary
    include: actions,decisions
```

## Repository

https://github.com/ComposioHQ/awesome-claude-skills/tree/master/meeting-insights-analyzer

## Included Files

- LICENSE.txt
- SKILL.md

## Triggers

- Summarize this meeting transcript
- Extract action items and owners from notes
- Create a decision log from this meeting

## Features

- Captures decisions, risks, and action items
- Assigns owners and due dates when available
- Outputs concise recap formats

## Best For

- PMs and team leads
- Operations teams capturing follow-ups
- Remote teams sharing meeting notes

## Tags

- Meetings
- Summaries
- Actions
- Notes
- Productivity
