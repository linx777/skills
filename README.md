# Skills Library

This repository is a catalog of reusable AI skills. Each skill is a self-contained package of guidance and metadata that an agent can load on demand to perform a focused task.

## What You Will Find Here

- Curated skill packs that cover UI/UX, performance, content creation, and data tasks.
- A consistent structure so skills can be discovered, loaded, and executed by tooling.
- Compiled guides that agents can read directly without additional context.

## How Skills Are Organized

- `skills/<skill-id>/` — one folder per skill (namespaces are allowed, such as `skills/anthropic/<skill-id>/`)
- Each skill folder includes:
  - `README.md` — scope, intended users, and usage notes
  - `SKILL.md` — name, description, and triggers
  - `AGENTS.md` — compiled guide for agents
  - `metadata.json` — versioning and ownership details
  - `rules/` — source rule files and templates

## Current Skills

- `vercel-react-best-practices` — React and Next.js performance optimization guidance from Vercel Engineering.
- Unofficial pack under `skills/unofficial/`:
  - `landing-page-optimizer` — Conversion-focused landing page optimization playbook.
- Anthropic pack under `skills/anthropic/`:
  - `algorithmic-art`
  - `brand-guidelines`
  - `canvas-design`
  - `doc-coauthoring`
  - `docx`
  - `frontend-design`
  - `internal-comms`
  - `mcp-builder`
  - `pdf`
  - `pptx`
  - `skill-creator`
  - `slack-gif-creator`
  - `theme-factory`
  - `web-artifacts-builder`
  - `webapp-testing`
  - `xlsx`

## Learn More

Open any skill folder and start with its `README.md` to see what it covers and how it is meant to be used. For more detail, visit [https://aiagentskills.xyz/](https://aiagentskills.xyz/).
