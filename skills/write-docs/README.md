# write-docs

Writing SDK documentation for tldraw with a confident, code-first voice.

## Overview

Defines the tldraw voice, avoids AI tells, and covers mechanics like sentence case, contractions, frontmatter, MDX components, and code-heavy examples.

## Metadata

- Author: tldraw
- Downloads: 2.9k
- Stars: 44585
- Roles: Product Management
- Type: Agent Skill
- Last updated: 2026.1.7

## Compatibility

- Claude App
- Codex CLI
- Claude Code CLI
- tldraw
- Gemini CLI

## Setup

Command:

```bash
claude mcp add write-docs
```

YAML config:

```yaml
tools:
  - name: write-docs
    style: tldraw
    examples: true
```

## Repository

https://github.com/tldraw/tldraw/tree/main/.claude/skills/write-docs

## Included Files

- SKILL.md

## Triggers

- Author or update docs in apps/docs/content
- Need tone guidance and examples for API links or MDX components
- Ensure headings, frontmatter, and examples match tldraw style

## Features

- Describes the tldraw voice and patterns to emulate or avoid
- Lists mechanics: sentence case, active voice, contractions
- Provides frontmatter template and MDX component usage (FocusLines, Image, tables)

## Best For

- tldraw doc writers
- Developers documenting SDK examples
- Reviewers polishing doc tone

## Tags

- Docs
- tldraw
- Writing
- MDX
- Style
