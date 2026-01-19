# webapp-testing

Playwright-based toolkit for testing local web apps with screenshots and logs.

## Overview

Automates browser testing via Playwright scripts to verify frontend behavior, capture screenshots, and surface console/network logs. Ideal for smoke tests, debugging regressions, and UI validations.

## Metadata

- Author: Anthropic
- Downloads: 5.0k
- Stars: 42002
- Roles: DevOps
- Type: Agent Skill
- Last updated: 2025.12.1

## Compatibility

- Claude App
- Codex CLI
- Claude Code CLI
- Playwright
- Gemini CLI

## Setup

Command:

```bash
claude mcp add webapp-testing
```

YAML config:

```yaml
tools:
  - name: webapp-testing
    runner: playwright
    headless: true
```

## Repository

https://github.com/anthropics/skills/tree/main/skills/webapp-testing

## Included Files

- LICENSE.txt
- SKILL.md
- examples/
- scripts/

## Triggers

- Write a Playwright smoke test for my local app
- Capture screenshots and console logs for this page
- Validate UI flows in staging with Playwright

## Features

- Generates Playwright scripts for local or staging apps
- Captures screenshots, console, and network logs
- Supports headless runs for CI-friendly smoke tests

## Best For

- QA smoke tests on staging builds
- Debugging UI regressions quickly
- Automated validation of critical user flows

## Tags

- Playwright
- Testing
- QA
- Screenshots
- Browser
