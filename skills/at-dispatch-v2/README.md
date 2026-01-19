# at-dispatch-v2

Convert legacy AT_DISPATCH macros to AT_DISPATCH_V2 in ATen C++ code.

## Overview

Details the macro reordering, AT_WRAP usage, type-group expansion, and header includes needed to port ATen dispatch sites to the v2 API safely.

## Metadata

- Author: PyTorch
- Downloads: 2.0k
- Stars: 96650
- Roles: Backend
- Type: Agent Skill
- Last updated: 2025.11.2

## Compatibility

- Claude Code CLI
- Codex CLI
- PyTorch
- Gemini CLI

## Setup

Command:

```bash
claude mcp add at-dispatch-v2
```

YAML config:

```yaml
tools:
  - name: at-dispatch-v2
    header: Dispatch_v2
    macros: convert
```

## Repository

https://github.com/pytorch/pytorch/tree/main/.claude/skills/at-dispatch-v2

## Included Files

- SKILL.md

## Triggers

- Port AT_DISPATCH_* macros to AT_DISPATCH_V2
- Work on aten/native kernels that use dispatch macros
- User mentions Dispatch_v2.h or dispatch conversion

## Features

- Maps legacy macros to AT_EXPAND type groups
- Shows AT_WRAP lambda wrapping and argument order
- Calls out the required Dispatch_v2 include and conflict handling

## Best For

- PyTorch C++ contributors
- Maintainers modernizing ATen kernels
- Teams standardizing dispatch macros

## Tags

- PyTorch
- C++
- ATen
- Macros
- Refactor
