# write-e2e-tests

Writing Playwright E2E tests for tldraw in apps/examples/e2e or apps/dotcom/client/e2e.

## Overview

Covers file layout, required declarations, setup patterns, fixtures, editor interactions, and UI/event assertions for end-to-end coverage.

## Metadata

- Author: tldraw
- Downloads: 2.7k
- Stars: 44585
- Roles: Frontend
- Type: Agent Skill
- Last updated: 2026.1.6

## Compatibility

- Claude Code CLI
- Codex CLI
- tldraw
- Playwright
- Gemini CLI

## Setup

Command:

```bash
claude mcp add write-e2e-tests
```

YAML config:

```yaml
tools:
  - name: write-e2e-tests
    runner: playwright
    headless: true
```

## Repository

https://github.com/tldraw/tldraw/tree/main/.claude/skills/write-e2e-tests

## Included Files

- SKILL.md

## Triggers

- Add or update Playwright tests for tldraw UI flows
- Need fixtures and setup patterns for SDK examples or dotcom
- Test editor interactions or UI events via page.evaluate

## Features

- Describes e2e folder structure, fixtures, and naming conventions
- Provides setup patterns (setupOrReset, shared pages, shape fixtures)
- Shows editor interactions, UI selectors, and event assertions

## Best For

- tldraw QA contributors
- Engineers validating editor behavior
- Teams maintaining Playwright suites

## Tags

- Playwright
- tldraw
- E2E
- Testing
- UI
