# code-change-verification

Verifies diffs with targeted tests, risk notes, and merge-ready checklists.

## Overview

An OpenAI-authored preflight skill that inspects code changes, proposes focused tests, and flags behavioral risks before merge. It pairs static heuristics with lightweight plans to keep CI fast while raising confidence.

## Metadata

- Author: OpenAI
- Downloads: 7.2k
- Stars: 18363
- Roles: DevOps
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
claude mcp add code-change-verification
```

YAML config:

```yaml
tools:
  - name: code-change-verification
    tests: auto
    risk_threshold: medium
```

## Repository

https://github.com/openai/openai-agents-python/tree/main/.codex/skills/code-change-verification

## Included Files

- SKILL.md
- scripts/

## Triggers

- Verify this PR before merge
- Generate a test plan for this diff
- Explain risks in these code changes

## Features

- Runs static heuristics and suggests targeted tests
- Highlights behavioral risk areas with owners
- Outputs merge checklist with pass/fail signals

## Best For

- Engineers shipping PRs in CI
- Release managers needing preflight checks
- Teams gating merges on risk analysis

## Tags

- Testing
- CI/CD
- Risk Analysis
- PR Review
- Automation
