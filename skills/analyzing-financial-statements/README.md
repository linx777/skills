# analyzing-financial-statements

Breaks down financial statements into ratios, trends, and risk signals.

## Overview

A finance-focused analysis skill that reads balance sheets, income statements, and cash flows to surface KPIs, liquidity metrics, and variance narratives. It packages outputs for exec-ready briefs.

## Metadata

- Author: Anthropic
- Downloads: 5.9k
- Stars: 31097
- Roles: Data Science
- Type: Agent Skill
- Last updated: 2025.11.28

## Compatibility

- Claude App
- Codex CLI
- Claude Code CLI
- Gemini CLI

## Setup

Command:

```bash
claude mcp add analyzing-financial-statements
```

YAML config:

```yaml
tools:
  - name: analyzing-financial-statements
    outputs: ratios,summary
    format: markdown
```

## Repository

https://github.com/anthropics/claude-cookbooks/tree/main/skills/custom_skills/analyzing-financial-statements

## Included Files

- SKILL.md
- calculate_ratios.py
- interpret_ratios.py

## Triggers

- Analyze this company's financial statements
- Summarize liquidity and profitability ratios
- Create an exec brief from these filings

## Features

- Computes key ratios and trend lines
- Highlights risks, anomalies, and variance drivers
- Packages findings into concise briefs

## Best For

- FP&A and finance teams
- Investors reviewing filings
- Leadership needing quick financial reads

## Tags

- Finance
- Ratios
- Analysis
- Reports
- Data
