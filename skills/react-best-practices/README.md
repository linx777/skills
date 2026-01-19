# react-best-practices

Reviews React codebases for best practices, performance, and maintainability.

## Overview

A Vercel-backed skill that audits React apps for hooks correctness, component structure, and performance pitfalls. It produces actionable fixes and consistency checks for production-grade UI code.

## Metadata

- Author: Vercel
- Downloads: 4.6k
- Stars: 12675
- Roles: DevOps
- Type: Agent Skill
- Last updated: 2026.1.18

## Compatibility

- Claude Code CLI
- Codex CLI
- Claude App
- React 18+
- Gemini CLI

## Setup

Command:

```bash
claude mcp add react-best-practices
```

YAML config:

```yaml
tools:
  - name: react-best-practices
    framework: react
    mode: review
```

## Repository

https://github.com/vercel-labs/agent-skills/tree/main/skills/react-best-practices

## Included Files

- SKILL.md

## Triggers

- Review this React component for best practices
- Find hooks and state management issues in this code
- Improve performance in this React page

## Features

- Flags hooks misuse and stale dependency risks
- Suggests component structure and state cleanup
- Highlights performance and rendering bottlenecks

## Best For

- Frontend teams maintaining React apps
- Engineers reviewing PRs for best practices
- Projects hardening performance and code quality

## Tags

- React
- Best Practices
- Performance
- Code Review
- Frontend
