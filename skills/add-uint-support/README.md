# add-uint-support

Add unsigned integer (uint16/uint32/uint64) support to PyTorch operators by updating AT_DISPATCH macros.

## Overview

Walks through converting dispatch sites to AT_DISPATCH_V2, expanding type groups with unsigned macros, and pairing the changes with regression tests.

## Metadata

- Author: PyTorch
- Downloads: 2.1k
- Stars: 96650
- Roles: Backend
- Type: Agent Skill
- Last updated: 2025.11.2

## Compatibility

- Claude Code CLI
- Codex CLI
- PyTorch
- Gemini CLI

## Repository

https://github.com/pytorch/pytorch/tree/main/.claude/skills/add-uint-support

## Included Files

- SKILL.md

## Triggers

- Add uint16/uint32/uint64 coverage to an ATen operator
- User mentions unsigned or barebones unsigned type support
- Follow up after converting a kernel to AT_DISPATCH_V2

## Features

- Explains AT_DISPATCH_V2 patterns and unsigned type groups
- Shows how to append AT_BAREBONES_UNSIGNED_TYPES or AT_INTEGRAL_TYPES_V2
- Pairs macro updates with targeted regression tests and overflow checks

## Best For

- PyTorch kernel contributors
- Maintainers extending dtype parity across CPU/GPU
- Reviewers checking unsigned dispatch changes

## Tags

- PyTorch
- ATen
- Dispatch
- Unsigned
- C++
