# g2-legend-expert

Expert guidance for G2 legend rendering, layout, and interaction.

## Overview

Covers legend inference, component creation, layout sizing, marker processing, and interaction handling for legendCategory and legendContinuous.

## Metadata

- Author: antvis
- Downloads: 1.8k
- Stars: 12508
- Roles: Frontend
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
claude mcp add g2-legend-expert
```

YAML config:

```yaml
tools:
  - name: g2-legend-expert
    components: legendCategory,legendContinuous
    layout: computePadding
```

## Repository

https://github.com/antvis/G2/tree/v5/.claude/skills/g2-legend-expert

## Included Files

- SKILL.md
- knowledge/

## Triggers

- Implement or debug legend rendering in G2
- Adjust legend layout or sizing
- Handle marker inference and scale analysis

## Features

- Explains legend inference from scales and channels
- Details category vs continuous component behavior
- Describes layout sizing, padding, and rendering options

## Best For

- G2 maintainers
- Engineers customizing legends
- Reviewers debugging legend behavior

## Tags

- G2
- Legends
- Layout
- Visualization
- Frontend
