# docs-sync

Syncs code changes with documentation, ensuring drift-free releases.

## Overview

Monitors diffs, updates docs, and creates PRs or issues when documentation lags behind. Keeps developer and user docs aligned with shipped behavior.

## Metadata

- Author: OpenAI
- Downloads: 5.1k
- Stars: 18363
- Roles: Product Management
- Type: Agent Skill
- Last updated: 2026.1.15

## Compatibility

- Codex CLI
- Claude Code CLI
- GitHub Actions
- Gemini CLI

## Repository

https://github.com/openai/openai-agents-python/tree/main/.codex/skills/docs-sync

## Included Files

- SKILL.md
- references/

## Triggers

- Sync docs with these code changes
- Open a PR to update documentation
- Flag drift between code and docs

## Features

- Detects doc drift after code changes
- Drafts updates and optional PRs
- Supports CI gating for doc freshness

## Best For

- Maintainers with doc-heavy repos
- Release teams shipping user-facing changes
- Docs writers collaborating with engineering

## Tags

- Docs
- CI
- Automation
- Sync
- PRs
