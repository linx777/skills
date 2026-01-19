# pr-draft-summary

Creates PR draft summaries with risk notes and next actions.

## Overview

Generates concise PR digests highlighting changes, risks, tests, and reviewers needed. Keeps stakeholders in sync and accelerates review cycles.

## Metadata

- Author: OpenAI
- Downloads: 6.2k
- Stars: 18363
- Roles: Product Management
- Type: Agent Skill
- Last updated: 2026.1.10

## Compatibility

- Codex CLI
- Claude Code CLI
- GitHub Actions
- Gemini CLI

## Setup

Command:

```bash
claude mcp add pr-draft-summary
```

YAML config:

```yaml
tools:
  - name: pr-draft-summary
    format: markdown
    include: risks,tests
```

## Repository

https://github.com/openai/openai-agents-python/tree/main/.codex/skills/pr-draft-summary

## Included Files

- SKILL.md

## Triggers

- Summarize this PR before review
- List risks and missing tests for this diff
- Draft reviewer notes for this change

## Features

- Creates structured PR summaries
- Highlights risks and test coverage gaps
- Adds reviewer and owner suggestions

## Best For

- Developers prepping PRs
- Reviewers needing quick context
- Release managers tracking changes

## Tags

- PR
- Summary
- Risks
- Testing
- Reviews
