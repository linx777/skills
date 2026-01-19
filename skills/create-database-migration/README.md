# create-database-migration

Create database migrations for Ghost's MySQL schema.

## Overview

Uses slimer to scaffold migrations, updates schema.js, runs knex-migrator and integrity tests, and points to examples and rules.

## Metadata

- Author: TryGhost
- Downloads: 2.5k
- Stars: 51602
- Roles: Backend
- Type: Agent Skill
- Last updated: 2025.12.2

## Compatibility

- Claude Code CLI
- Codex CLI
- Ghost
- MySQL
- Gemini CLI

## Repository

https://github.com/TryGhost/Ghost/tree/main/.claude/skills/create-database-migration

## Included Files

- SKILL.md
- examples.md
- rules.md

## Triggers

- Add tables, columns, or settings in the Ghost database
- Run slimer migration scaffolding
- Update schema definitions and integrity tests

## Features

- Explains slimer migration command and directory layout
- Covers updating schema.js and exporter table lists
- Lists required tests (knex-migrator, schema integrity, unit tests)

## Best For

- Ghost core maintainers
- Contributors changing database schema
- Engineers validating migrations before release

## Tags

- Ghost
- Migration
- MySQL
- Schema
- Knex
