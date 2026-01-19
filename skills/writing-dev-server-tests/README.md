# writing-dev-server-tests

Guides writing HMR/dev server tests in Bun’s test/bake harness.

## Overview

Explains devTest utilities, file layout, fixtures, and how to assert hot reload behavior and errors without using raw fs calls.

## Metadata

- Author: oven-sh
- Downloads: 2.3k
- Stars: 86361
- Roles: DevOps
- Type: Agent Skill
- Last updated: 2025.12.25

## Compatibility

- Claude Code CLI
- Codex CLI
- Bun
- Gemini CLI

## Repository

https://github.com/oven-sh/bun/tree/main/.claude/skills/writing-dev-server-tests

## Included Files

- SKILL.md

## Triggers

- Add or fix Bun dev server or hot reload tests
- Work in test/bake dev or dev-and-prod suites
- Need guidance on devTest APIs and expected errors

## Features

- Maps bake harness files and test categories
- Shows devTest usage with dev.fetch/dev.client and reload assertions
- Highlights using dev.write/patch/delete instead of fs for hot reload

## Best For

- Bun contributors expanding regression coverage
- Maintainers debugging dev server behavior
- QA engineers validating HMR flows

## Tags

- Bun
- Testing
- Dev Server
- HMR
- Fixtures
