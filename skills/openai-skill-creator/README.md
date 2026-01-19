# openai-skill-creator

Sample skill that demonstrates OpenAI Codex skill anatomy for Rust projects.

## Overview

A reference implementation shipped with Codex RS showing how to structure skill assets, handlers, and metadata. Perfect for Rust developers bootstrapping custom skills.

## Metadata

- Author: OpenAI
- Downloads: 2.5k
- Stars: 56256
- Roles: DevOps
- Type: Agent Skill
- Last updated: 2026.1.7

## Compatibility

- Codex CLI
- Claude Code CLI
- Gemini CLI

## Setup

Command:

```bash
claude mcp add openai-skill-creator
```

YAML config:

```yaml
tools:
  - name: skill-creator
    language: rust
    template: sample
```

## Repository

https://github.com/openai/codex/tree/main/codex-rs/core/src/skills/assets/samples/skill-creator

## Included Files

- SKILL.md
- license.txt
- scripts/

## Triggers

- Show me a Rust skill template
- Explain Codex skill file structure
- Generate a Rust handler from the sample

## Features

- Rust-first sample with annotated code
- Demonstrates SKILL.md and manifest wiring
- Includes starter handler logic

## Best For

- Rust developers learning Codex skills
- Teams standardizing skill structure
- Workshops teaching skill basics

## Tags

- Rust
- Template
- Codex
- Skills
- Sample
