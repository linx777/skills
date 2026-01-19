# rule-identifier

Extracts implicit rules from codebases and turns them into enforceable policies.

## Overview

A writing-rules helper that scans repositories, surfaces unwritten conventions, and drafts .rules files for consistent guardrails. It keeps style, safety, and dependency policies explicit for teams.

## Metadata

- Author: Anthropic
- Downloads: 3.2k
- Stars: 56950
- Roles: Product Management
- Type: Agent Skill
- Last updated: 2025.11.17

## Compatibility

- Claude Code CLI
- Codex CLI
- Claude App
- Gemini CLI

## Setup

Command:

```bash
claude mcp add rule-identifier
```

YAML config:

```yaml
tools:
  - name: rule-identifier
    output: rules
    mode: audit
```

## Repository

https://github.com/anthropics/claude-code/tree/main/plugins/hookify/skills/writing-rules

## Included Files

- SKILL.md

## Triggers

- Infer coding rules from this repo
- Draft .rules for lint and style enforcement
- Document implicit guardrails for new contributors

## Features

- Scans code to surface implicit conventions
- Generates .rules files with rationales and examples
- Maps rules to lint or CI enforcement hooks

## Best For

- Teams formalizing unwritten practices
- Repos lacking explicit guardrails
- Onboarding docs that explain style decisions

## Tags

- Rules
- Governance
- Docs
- Lint
- Conventions
