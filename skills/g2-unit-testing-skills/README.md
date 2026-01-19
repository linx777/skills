# g2-unit-testing-skills

Guidelines and best practices for writing unit tests in the AntV G2 visualization library.

## Overview

Explains test directory structure, Jest patterns, and organization for unit vs integration plots across APIs, animation, interaction, and more.

## Metadata

- Author: antvis
- Downloads: 2.0k
- Stars: 12508
- Roles: DevOps
- Type: Agent Skill
- Last updated: 2025.12.31

## Compatibility

- Claude Code CLI
- Codex CLI
- G2
- Gemini CLI

## Setup

Command:

```bash
claude mcp add g2-unit-testing-skills
```

YAML config:

```yaml
tools:
  - name: g2-testing
    framework: jest
    scope: unit+plots
```

## Repository

https://github.com/antvis/G2/tree/v5/.claude/skills/g2-testing

## Included Files

- SKILL.md

## Triggers

- Write unit tests for G2 modules
- Organize plot integration tests
- Set up Jest cases for API/animation/interaction

## Features

- Defines unit vs integration directories
- Provides testing structure examples
- Lists focus areas for rendering and behavior coverage

## Best For

- G2 contributors writing tests
- QA adding visualization coverage
- Reviewers enforcing test structure

## Tags

- G2
- Testing
- Jest
- Visualization
- Coverage
