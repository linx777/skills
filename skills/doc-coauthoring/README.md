# doc-coauthoring

Structured three-stage workflow for drafting and refining documentation.

## Overview

Guides teams through context gathering, iterative structuring, and reader testing for docs. Ideal for PRDs, RFCs, decision records, and proposals where clarity, audience fit, and reviewability matter.

## Metadata

- Author: Anthropic
- Downloads: 12.0k
- Stars: 42002
- Roles: Product Management
- Type: Agent Skill
- Last updated: 2025.12.4

## Compatibility

- Claude Code CLI
- Codex CLI
- Claude App
- Gemini CLI

## Setup

Command:

```bash
claude mcp add doc-coauthoring
```

YAML config:

```yaml
tools:
  - name: doc-coauthoring
    workflow: guided
    stages: 3
```

## Repository

https://github.com/anthropics/skills/tree/main/skills/doc-coauthoring

## Included Files

- SKILL.md

## Triggers

- Help me draft a PRD with a co-authoring flow
- Guide me through a design doc with reader testing
- Set up a structured workflow for this RFC

## Features

- Stage 1 context gathering with clarifying questions
- Section-by-section brainstorming and refinement
- Reader-testing pass to surface gaps before sharing

## Best For

- PRDs, RFCs, and design docs
- Decision records and proposals
- Leadership updates that need airtight clarity

## Tags

- Docs
- PRD
- RFC
- Collaboration
- Writing
