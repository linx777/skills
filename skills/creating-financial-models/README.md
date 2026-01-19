# creating-financial-models

Builds structured financial models with drivers, scenarios, and sanity checks.

## Overview

Generates three-statement models, sensitivity tabs, and QA checks. It keeps assumptions explicit, formulas audited, and outputs presentation-ready for stakeholders.

## Metadata

- Author: Anthropic
- Downloads: 6.6k
- Stars: 31097
- Roles: Data Science
- Type: Agent Skill
- Last updated: 2025.11.28

## Compatibility

- Claude App
- Codex CLI
- Claude Code CLI
- XLSX
- Gemini CLI

## Setup

Command:

```bash
claude mcp add creating-financial-models
```

YAML config:

```yaml
tools:
  - name: creating-financial-models
    format: xlsx
    scenarios: true
```

## Repository

https://github.com/anthropics/claude-cookbooks/tree/main/skills/custom_skills/creating-financial-models

## Included Files

- SKILL.md
- dcf_model.py
- sensitivity_analysis.py

## Triggers

- Build a three-statement model for this business
- Add scenario analysis to this model
- Audit formulas and assumptions in this sheet

## Features

- Creates linked three-statement models with drivers
- Adds scenarios, sensitivities, and sanity checks
- Formats outputs for stakeholder-ready decks

## Best For

- Finance teams modeling new products
- Operators testing scenarios quickly
- Analysts auditing spreadsheet risk

## Tags

- Finance
- Modeling
- XLSX
- Assumptions
- Scenarios
