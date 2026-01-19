# test-coverage-improver

Suggests targeted tests to raise coverage with minimal noise.

## Overview

Analyzes coverage reports and diffs to propose high-impact tests. It balances speed and confidence by focusing on risky paths and untested logic.

## Metadata

- Author: OpenAI
- Downloads: 6.7k
- Stars: 18363
- Roles: DevOps
- Type: Agent Skill
- Last updated: 2026.1.14

## Compatibility

- Codex CLI
- Claude Code CLI
- GitHub Actions
- Gemini CLI

## Repository

https://github.com/openai/openai-agents-python/tree/main/.codex/skills/test-coverage-improver

## Included Files

- SKILL.md

## Triggers

- Recommend tests to raise coverage
- Analyze this diff for untested paths
- Plan targeted tests under time constraints

## Features

- Reads coverage reports and diffs
- Prioritizes risky or untested code paths
- Suggests lean tests to hit thresholds

## Best For

- CI pipelines enforcing coverage
- Teams under release pressure
- Maintainers addressing flaky coverage gaps

## Tags

- Coverage
- Testing
- CI
- Risk
- Automation
