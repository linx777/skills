# code-change-verification-js

Node-focused code change verifier with targeted checks and quick tests.

## Overview

A JS/TS flavor of code-change verification that inspects diffs, proposes Playwright/Jest snippets, and highlights runtime risks. Keeps CI lean while raising reviewer confidence.

## Metadata

- Author: OpenAI
- Downloads: 5.4k
- Stars: 2171
- Roles: DevOps
- Type: Agent Skill
- Last updated: 2026.1.10

## Compatibility

- Codex CLI
- Claude Code CLI
- GitHub Actions
- Gemini CLI

## Repository

https://github.com/openai/openai-agents-js/tree/main/.codex/skills/code-change-verification

## Included Files

- SKILL.md
- scripts/

## Triggers

- Verify JS/TS changes before merge
- Suggest Jest or Playwright checks for this diff
- Highlight runtime risks in this PR

## Features

- Analyzes diffs for JS/TS-specific risks
- Suggests lightweight tests and scripts
- Outputs merge-ready checklists

## Best For

- Node and frontend teams
- Release managers needing quick verification
- CI pipelines guarding PR merges

## Tags

- JavaScript
- Testing
- CI
- Risks
- PR Review
