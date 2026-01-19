# video-downloader

Downloads videos with format, quality, and metadata options.

## Overview

Handles video download workflows by choosing formats, resolutions, and metadata outputs for archival or analysis.

## Metadata

- Author: Prathit
- Downloads: 6.8k
- Stars: 21251
- Roles: DevOps
- Type: Agent Skill
- Last updated: 2025.12.29

## Compatibility

- Claude Code CLI
- Codex CLI
- Claude App
- Gemini CLI

## Setup

Command:

```bash
claude mcp add video-downloader
```

YAML config:

```yaml
tools:
  - name: video-downloader
    formats: mp4,webm
    metadata: true
```

## Repository

https://github.com/ComposioHQ/awesome-claude-skills/tree/master/video-downloader

## Included Files

- LICENSE.txt
- SKILL.md

## Triggers

- Download this video in MP4 format
- Fetch a video with metadata and captions
- Choose the best resolution for this URL

## Features

- Selects formats and resolutions based on requirements
- Captures metadata and optional captions
- Outputs a clear download plan

## Best For

- Teams archiving video assets
- Analysts collecting media samples
- Ops users automating media retrieval

## Tags

- Video
- Download
- Media
- Automation
- Utilities
