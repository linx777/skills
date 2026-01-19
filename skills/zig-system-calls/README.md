# zig-system-calls

Guides using bun.sys for system calls and file I/O in Zig instead of std.fs/std.posix.

## Overview

Shows bun.sys.File wrappers, Maybe(T) error handling, cross-platform flags, and lower-level open/read/write patterns.

## Metadata

- Author: oven-sh
- Downloads: 1.7k
- Stars: 86361
- Roles: Backend
- Type: Agent Skill
- Last updated: 2025.12.25

## Compatibility

- Claude Code CLI
- Codex CLI
- Bun
- Gemini CLI

## Setup

Command:

```bash
claude mcp add zig-system-calls
```

YAML config:

```yaml
tools:
  - name: zig-system-calls
    platforms: [macos, linux, windows]
    api: bun.sys
```

## Repository

https://github.com/oven-sh/bun/tree/main/.claude/skills/zig-system-calls

## Included Files

- SKILL.md

## Triggers

- Implement file or syscall logic in Zig for Bun
- Need error-aware wrappers versus raw std.fs
- Handle cross-platform file operations with bun.sys

## Features

- Demonstrates bun.sys.File open/read/write/stat helpers
- Explains Maybe(T) error patterns and unwrap flows
- Covers bun.O flags and low-level open/read/write examples

## Best For

- Zig developers extending Bun syscalls
- Engineers porting fs usage to bun.sys
- Contributors needing cross-platform file handling

## Tags

- Zig
- Bun
- Syscalls
- File I/O
- bun.sys
