# infographic-template-updater

Update AntV Infographic template catalogs and prompt lists when new templates are added.

## Overview

Guides collecting new template keys, updating template lists across SKILLs, playground prompts, and syntax references while preserving ordering.

## Metadata

- Author: antvis
- Downloads: 1.9k
- Stars: 3852
- Roles: Product Management
- Type: Agent Skill
- Last updated: 2026.1.5

## Compatibility

- Claude Code CLI
- Codex CLI
- Infographic
- Gemini CLI

## Setup

Command:

```bash
claude mcp add infographic-template-updater
```

YAML config:

```yaml
tools:
  - name: infographic-template-updater
    templates: src/templates
    prompts: sync
```

## Repository

https://github.com/antvis/Infographic/tree/main/.skills/infographic-template-updater

## Included Files

- SKILL.md

## Triggers

- Add new infographic templates in src/templates
- Sync template lists across creator and syntax prompts
- Verify gallery mappings for new templates

## Features

- Collects template keys including spread compositions
- Updates creator, playground, and syntax prompt lists
- Keeps ordering and performs ripgrep sanity checks

## Best For

- Infographic maintainers
- Contributors adding templates
- Docs owners syncing template references

## Tags

- Infographic
- Templates
- Docs
- Sync
- Lists
