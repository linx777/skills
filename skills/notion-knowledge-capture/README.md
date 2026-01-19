# notion-knowledge-capture

Captures and structures knowledge into Notion with tags and backlinks.

## Overview

Ingests notes, specs, and meeting recaps into Notion databases with metadata, backlinks, and summaries. Keeps knowledge bases organized and searchable.

## Metadata

- Author: OpenAI
- Downloads: 5.0k
- Stars: 1616
- Roles: Product Management
- Type: Agent Skill
- Last updated: 2025.12.19

## Compatibility

- Claude App
- Codex CLI
- Claude Code CLI
- Notion API
- Gemini CLI

## Setup

Command:

```bash
claude mcp add notion-knowledge-capture
```

YAML config:

```yaml
tools:
  - name: notion-knowledge-capture
    links: backlinks
    tags: auto
```

## Repository

https://github.com/openai/skills/tree/main/skills/.curated/notion-knowledge-capture

## Included Files

- LICENSE.txt
- SKILL.md
- evaluations/
- examples/
- reference/

## Triggers

- Ingest these notes into Notion with tags
- Backlink related specs and docs
- Summarize and store this meeting recap

## Features

- Creates structured Notion entries with tags
- Adds backlinks between related docs
- Summarizes content for quick scanning

## Best For

- Knowledge management teams
- Project spaces in Notion
- Research groups sharing notes

## Tags

- Notion
- Knowledge Base
- Docs
- Backlinks
- Tags
