# electron-chromium-upgrade

Guide for performing Chromium version upgrades in Electron roller/chromium/main.

## Overview

Covers Phase One patch application via `e sync --3` and `e patches`, and Phase Two build fixes with `e build -k 999`, including commit rules and summaries.

## Metadata

- Author: Electron
- Downloads: 3.5k
- Stars: 119754
- Roles: DevOps
- Type: Agent Skill
- Last updated: 2025.12.19

## Compatibility

- Claude Code CLI
- Codex CLI
- Electron
- Chromium
- Gemini CLI

## Setup

Command:

```bash
claude mcp add electron-chromium-upgrade
```

YAML config:

```yaml
tools:
  - name: electron-chromium-upgrade
    strategy: staged
    tests: smoke
```

## Repository

https://github.com/electron/electron/tree/main/.claude/skills/electron-chromium-upgrade

## Included Files

- SKILL.md
- references/

## Triggers

- Run e sync --3 and resolve patch conflicts during a roll
- Fix build failures on roller/chromium/main
- Write upgrade summaries and commits for patch fixes

## Features

- Step-by-step loop for applying patches with git am and e patches
- Phase Two build triage with e build -k 999 and start --version
- Commit rules and cautions against dropping patches prematurely

## Best For

- Electron maintainers handling Chromium upgrades
- Contributors debugging patch and build failures
- Release engineers coordinating rollouts

## Tags

- Electron
- Chromium
- Upgrades
- Patches
- Build
