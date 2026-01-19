# command-development

Scaffolds plugin commands with typed schemas, validation, and docs.

## Overview

A plugin-dev helper that drafts new command definitions, covers input/output schemas, and seeds tests. It keeps error handling, telemetry hooks, and README usage examples consistent across a command surface.

## Metadata

- Author: Anthropic
- Downloads: 3.5k
- Stars: 56950
- Roles: DevOps
- Type: Agent Skill / Plugin Dev
- Last updated: 2025.11.17

## Compatibility

- Claude Code CLI
- Codex CLI
- Claude App
- Gemini CLI

## Setup

Command:

```bash
claude mcp add command-development
```

YAML config:

```yaml
tools:
  - name: command-development
    language: typescript
    templates: command
```

## Repository

https://github.com/anthropics/claude-code/tree/main/plugins/plugin-dev/skills/command-development

## Included Files

- README.md
- SKILL.md
- examples/
- references/

## Triggers

- Scaffold a new plugin command with validation
- Add typed inputs and outputs to this command
- Write tests and docs for a command surface

## Features

- Generates command manifests with input validation and typings
- Includes error handling, telemetry, and test stubs
- Produces README snippets and usage examples automatically

## Best For

- Plugin developers adding new commands
- Teams standardizing command behaviors
- Maintainers shipping CLI-driven workflows

## Tags

- CLI
- Plugins
- TypeScript
- Validation
- Docs
