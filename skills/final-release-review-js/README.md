# final-release-review-js

Runs release readiness checks for JS/TS packages with owners and risks.

## Overview

Pulls diff, test, and docs signals for Node projects to deliver a concise release brief. Flags blockers, assigns owners, and suggests rollout sequencing.

## Metadata

- Author: OpenAI
- Downloads: 3.8k
- Stars: 2171
- Roles: DevOps
- Type: Agent Skill
- Last updated: 2026.1.17

## Compatibility

- Codex CLI
- Claude Code CLI
- GitHub Actions
- Gemini CLI

## Setup

Command:

```bash
claude mcp add final-release-review-js
```

YAML config:

```yaml
tools:
  - name: final-release-review
    runtime: node
    checklist: full
```

## Repository

https://github.com/openai/openai-agents-js/tree/main/.codex/skills/final-release-review

## Included Files

- SKILL.md
- references/
- scripts/

## Triggers

- Run a JS release review
- List risks and owners for this package release
- Summarize readiness across code, tests, docs

## Features

- Compiles JS/TS release risks and blockers
- Checks tests, docs, and versioning signals
- Produces a short release brief with owners

## Best For

- Node release managers
- Teams shipping npm packages
- CI pipelines gating production releases

## Tags

- JavaScript
- Release
- Checklist
- Risks
- CI
