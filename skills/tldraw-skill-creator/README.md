# tldraw-skill-creator

Guide for creating effective Claude skills in the tldraw repo.

## Overview

Explains what skills provide, concise writing principles, degrees of freedom, and the anatomy of SKILL.md plus optional scripts, references, and assets.

## Metadata

- Author: tldraw
- Downloads: 3.2k
- Stars: 44585
- Roles: DevOps
- Type: Agent Skill
- Last updated: 2026.1.7

## Compatibility

- Claude Code CLI
- Codex CLI
- tldraw
- Gemini CLI

## Setup

Command:

```bash
claude mcp add tldraw-skill-creator
```

YAML config:

```yaml
tools:
  - name: skill-creator
    platform: tldraw
    templates: true
```

## Repository

https://github.com/tldraw/tldraw/tree/main/.claude/skills/skill-creator

## Included Files

- LICENSE.txt
- SKILL.md
- references/
- scripts/

## Triggers

- Create or update a Claude skill in tldraw
- Write SKILL.md frontmatter and body for a skill
- Decide on scripts, references, or assets to bundle

## Features

- Explains skill scope and context budgeting
- Describes required frontmatter and skill anatomy
- Covers optional scripts/references/assets directories

## Best For

- tldraw contributors authoring skills
- Teams packaging workflows into skills
- Reviewers ensuring skills are token-efficient

## Tags

- Skills
- tldraw
- Claude
- Docs
- Structure
