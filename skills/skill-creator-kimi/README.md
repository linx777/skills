# skill-creator-kimi

Guide for creating effective skills in Kimi CLI with concise, structured content.

## Overview

Covers skill anatomy, degrees of freedom, progressive disclosure, and when to add scripts, references, or assets so Kimi skills stay focused and token-efficient.

## Metadata

- Author: MoonshotAI
- Downloads: 2.6k
- Stars: 3855
- Roles: DevOps
- Type: Agent Skill
- Last updated: 2026.1.6

## Compatibility

- Kimi CLI
- Claude Code CLI
- Codex CLI
- Gemini CLI

## Setup

Command:

```bash
claude mcp add skill-creator-kimi
```

YAML config:

```yaml
tools:
  - name: skill-creator
    platform: kimi-cli
    resources: optional
```

## Repository

https://github.com/MoonshotAI/kimi-cli/tree/main/src/kimi_cli/skills/skill-creator

## Included Files

- SKILL.md

## Triggers

- Create or update a Kimi CLI skill
- Decide what to include in SKILL.md vs scripts/references/assets
- Need principles for concise, high-impact skill content

## Features

- Explains skill anatomy and required metadata
- Guides degree-of-freedom choices (text, pseudocode, scripts)
- Uses progressive disclosure to manage context size

## Best For

- Kimi CLI contributors authoring skills
- Teams packaging workflows for Kimi
- Maintainers enforcing consistent skill structure

## Tags

- Kimi
- Skills
- CLI
- Docs
- Structure
