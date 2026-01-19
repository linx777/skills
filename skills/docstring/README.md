# docstring

Write docstrings for PyTorch functions and methods following PyTorch conventions.

## Overview

Covers raw-string Sphinx formatting, signature lines, sections, math blocks, cross-references, and examples so docs stay aligned with torch/_tensor_docs.py patterns.

## Metadata

- Author: PyTorch
- Downloads: 3.3k
- Stars: 96650
- Roles: Product Management
- Type: Agent Skill
- Last updated: 2025.10.26

## Compatibility

- Claude Code CLI
- Codex CLI
- PyTorch
- Gemini CLI

## Setup

Command:

```bash
claude mcp add docstring
```

YAML config:

```yaml
tools:
  - name: docstring
    format: pytorch
    examples: true
```

## Repository

https://github.com/pytorch/pytorch/tree/main/.claude/skills/docstring

## Included Files

- SKILL.md

## Triggers

- Draft or update a PyTorch docstring
- Ensure raw-string Sphinx formatting for torch APIs
- Add examples and cross-references for functions or methods

## Features

- Defines required structure: signature, description, args, keyword args
- Shows Sphinx math, admonitions, and cross-reference patterns
- Emphasizes examples, defaults, and formatting rules

## Best For

- PyTorch maintainers documenting APIs
- Contributors cleaning up docs formatting
- Reviewers validating docstring structure

## Tags

- Docs
- PyTorch
- Sphinx
- Docstring
- Python
