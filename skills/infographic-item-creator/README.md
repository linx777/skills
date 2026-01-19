# infographic-item-creator

Generate or update infographic Item components in src/designs/items.

## Overview

Covers reading item prompts, layout props, registerItem composites, and self-checks against allowed components and indexes.

## Metadata

- Author: antvis
- Downloads: 1.8k
- Stars: 3852
- Roles: Frontend
- Type: Agent Skill
- Last updated: 2026.1.4

## Compatibility

- Claude Code CLI
- Codex CLI
- Infographic
- Gemini CLI

## Setup

Command:

```bash
claude mcp add infographic-item-creator
```

YAML config:

```yaml
tools:
  - name: infographic-item-creator
    language: typescript
    refs: item-prompt
```

## Repository

https://github.com/antvis/Infographic/tree/main/.skills/infographic-item-creator

## Included Files

- SKILL.md
- references/

## Triggers

- Implement or modify infographic items
- Compute layout with getElementBounds and registerItem
- Check allowed components and composites

## Features

- Points to item prompt references
- Details props, layout computation, and registration
- Includes self-checks for indexes and component rules

## Best For

- Infographic component authors
- Teams extending item visuals
- Reviewers ensuring item constraints

## Tags

- Infographic
- Components
- TypeScript
- Layout
- UI
