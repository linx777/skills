# skill-development

Coaches authors through end-to-end skill creation with tests and safety notes.

## Overview

A plugin-dev mentor that covers ideation, triggers, YAML metadata, and validation. It generates SKILL.md drafts, safety callouts, and minimal test scaffolds to keep contributions consistent.

## Metadata

- Author: Anthropic
- Downloads: 4.4k
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
claude mcp add skill-development
```

YAML config:

```yaml
tools:
  - name: skill-development
    templates: true
    safety: reminders
```

## Repository

https://github.com/anthropics/claude-code/tree/main/plugins/plugin-dev/skills/skill-development

## Included Files

- SKILL.md
- references/

## Triggers

- Walk me through drafting a new skill
- Add safety guidance to this SKILL.md
- Generate triggers and YAML metadata for my skill

## Features

- Provides SKILL.md and metadata templates
- Includes safety and evaluation reminders
- Adds lightweight tests for handlers or tools

## Best For

- Contributors adding new skills
- Maintainers standardizing documentation
- Teams shipping skills with safety built in

## Tags

- Skills
- Authoring
- Templates
- Safety
- Docs
