# infographic-syntax-creator

Generate AntV Infographic syntax outputs from user content.

## Overview

Describes how to extract structure, select templates, and produce valid plain syntax with strict formatting and constraints.

## Metadata

- Author: antvis
- Downloads: 1.9k
- Stars: 3852
- Roles: Product Management
- Type: Agent Skill
- Last updated: 2026.1.16

## Compatibility

- Claude App
- Codex CLI
- Claude Code CLI
- Infographic
- Gemini CLI

## Setup

Command:

```bash
claude mcp add infographic-syntax-creator
```

YAML config:

```yaml
tools:
  - name: infographic-syntax-creator
    output: plain
    prompt: references/prompt.md
```

## Repository

https://github.com/antvis/Infographic/tree/main/.skills/infographic-syntax-creator

## Included Files

- SKILL.md
- references/

## Triggers

- Turn content into AntV Infographic DSL
- Pick templates for sequences, lists, or comparisons
- Output infographic <template> syntax in a plain block

## Features

- Enforces single plain code block with template line
- Specifies indentation, key/value, and array rules
- Lists constraints for compare templates and formatting

## Best For

- Developers generating infographic syntax
- Writers formatting content for AntV DSL
- Teams validating infographic outputs

## Tags

- Infographic
- DSL
- Syntax
- Templates
- Formatting
