# gemini-pr-creator

Creates PRs that follow repository templates and standards.

## Overview

Walks through finding PR templates, drafting descriptions with checklists, and using the gh CLI with Conventional Commit titles for Gemini CLI changes.

## Metadata

- Author: Google Gemini
- Downloads: 2.9k
- Stars: 91053
- Roles: Product Management
- Type: Agent Skill
- Last updated: 2026.1.14

## Compatibility

- Gemini CLI
- Codex CLI
- Claude Code CLI
- GitHub

## Repository

https://github.com/google-gemini/gemini-cli/tree/main/.gemini/skills/pr-creator

## Included Files

- SKILL.md

## Triggers

- Create a PR for Gemini CLI changes
- Need to locate and follow PR template files
- User invokes /pr or asks for gh CLI steps

## Features

- Searches for templates under .github/PULL_REQUEST_TEMPLATE*
- Keeps headings and checklists intact and marks applicable items
- Uses gh pr create with body file and Conventional Commit title guidance

## Best For

- Gemini CLI contributors
- Maintainers enforcing PR standards
- Teams automating PR creation

## Tags

- PR
- Gemini
- Docs
- Checklists
- Contribution
