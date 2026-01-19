# cache-components

Audits Next.js routes to prevent cache stampedes and stale ISR responses.

## Overview

A Vercel-built skill that inspects Next.js caching primitives, flags risky fetches, and proposes safe revalidation strategies. It keeps route handlers, RSC fetches, and ISR pages aligned with platform best practices for consistent performance.

## Metadata

- Author: Vercel Labs
- Downloads: 4.3k
- Stars: 137153
- Roles: Frontend
- Type: Agent Skill
- Last updated: 2026.1.8

## Compatibility

- Claude Code CLI
- Codex CLI
- Claude App
- Next.js 14+
- Gemini CLI

## Repository

https://github.com/vercel/next.js/tree/canary/.claude-plugin/plugins/cache-components/skills/cache-components

## Included Files

- PATTERNS.md
- REFERENCE.md
- SKILL.md
- TROUBLESHOOTING.md

## Triggers

- Audit caching for this Next.js route
- Patch ISR settings to avoid stale data
- Explain how this fetch will be cached on Vercel

## Features

- Detects cache stampede risks and missing revalidate settings
- Reviews RSC fetch usage and recommends cache modes
- Suggests safe ISR defaults with incremental invalidation plans

## Best For

- Next.js teams shipping ISR-heavy apps
- Avoiding stale data and cache regressions
- Performance-focused frontend engineers

## Tags

- Next.js
- Caching
- Performance
- ISR
- Vercel
