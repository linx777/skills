# plugin-settings

Store Claude Code plugin configuration in .claude/plugin-name.local.md files with YAML frontmatter.

## Overview

Documents the plugin settings pattern, showing how to read/write .local.md files for per-project configuration, parse YAML frontmatter, and wire settings into hooks, commands, or agents.

## Metadata

- Author: Anthropic
- Downloads: 2.4k
- Stars: 56950
- Roles: DevOps
- Type: Agent Skill / Plugin Dev
- Last updated: 2026.1.6

## Compatibility

- Claude Code CLI
- Codex CLI
- Claude App
- Gemini CLI

## Repository

https://github.com/anthropics/claude-plugins-official/tree/main/plugins/plugin-dev/skills/plugin-settings

## Included Files

- SKILL.md
- examples/
- references/
- scripts/

## Triggers

- Add configurable settings or state to a Claude Code plugin
- Parse YAML frontmatter from .claude/plugin-name.local.md
- Wire plugin configuration into hooks, commands, or agents

## Features

- Defines .claude/plugin-name.local.md structure with YAML frontmatter
- Shows parsing patterns and example scripts for hooks/commands
- Outlines lifecycle, gitignore guidance, and usage across plugin surfaces

## Best For

- Plugin developers adding user-configurable settings
- Teams storing per-project plugin state
- Maintainers standardizing configuration patterns

## Tags

- Plugins
- Settings
- YAML
- Configuration
- State
