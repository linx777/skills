# pr-draft-summary-js

Drafts PR summaries for JS/TS repos with risks and test prompts.

## Overview

Focuses on JavaScript and TypeScript diffs, producing reviewer-ready summaries, risk callouts, and suggested Jest/Playwright tests to accelerate approvals.

## Metadata

- Author: OpenAI
- Downloads: 4.9k
- Stars: 2171
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
claude mcp add pr-draft-summary-js
```

YAML config:

```yaml
tools:
  - name: pr-draft-summary
    runtime: node
    include: risks,tests
```

## Repository

https://github.com/openai/openai-agents-js/tree/main/.codex/skills/pr-draft-summary

## Included Files

- SKILL.md

## Triggers

- Summarize this JS/TS PR
- List risks and suggested tests for this diff
- Create reviewer notes for this change

## Features

- Generates JS-focused PR summaries
- Calls out risks and missing tests
- Adds suggested reviewers or owners

## Best For

- Frontend and Node teams
- Reviewers scanning large diffs
- Release managers tracking JS changes

## Tags

- PR
- JavaScript
- Summary
- Risks
- Testing
