# resource-curator

Find, evaluate, and maintain high-quality external resources for JavaScript concept docs.

## Overview

Includes auditing existing links, target counts per resource type, search queries for articles and videos, description formulas, and trusted sources.

## Metadata

- Author: leonardomso
- Downloads: 2.2k
- Stars: 66133
- Roles: Product Management
- Type: Agent Skill
- Last updated: 2026.1.6

## Compatibility

- Claude App
- Codex CLI
- Claude Code CLI
- Gemini CLI

## Setup

Command:

```bash
claude mcp add resource-curator
```

YAML config:

```yaml
tools:
  - name: resource-curator
    tags: difficulty,format
    output: list
```

## Repository

https://github.com/leonardomso/33-js-concepts/tree/master/.opencode/skill/resource-curator

## Included Files

- SKILL.md

## Triggers

- Add or refresh resources on a concept page
- Audit links for accuracy and freshness
- Curate resource lists with descriptions and icons

## Features

- Provides audit checklist for status, accuracy, and dates
- Defines target counts for references, articles, videos, courses, books
- Supplies search queries, trusted sources, and description formulas

## Best For

- Docs maintainers curating external links
- Community editors vetting contributions
- SEO/content strategists balancing beginner and advanced resources

## Tags

- Resources
- Curation
- JavaScript
- Docs
- Links
