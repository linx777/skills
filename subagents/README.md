# Claude Code Subagents

Subagents are focused assistants you can delegate to inside Claude Code. Each file in this folder defines a single role with a clear scope, tools, and model, so the main agent can offload work without expanding the overall context.

## Included Subagents

- `architect.md` - system design and architecture decisions
- `build-error-resolver.md` - diagnose and fix build errors
- `code-reviewer.md` - quality, maintainability, and security review
- `doc-updater.md` - keep documentation in sync with code changes
- `e2e-runner.md` - Playwright E2E test execution guidance
- `planner.md` - implementation planning and task breakdowns
- `refactor-cleaner.md` - refactor and dead code cleanup
- `security-reviewer.md` - vulnerability and risk analysis
- `tdd-guide.md` - test-driven development flow

## How to Use

1. Copy the subagent files into your Claude Code agents directory (for example, `~/.claude/agents/` or a project-level `.claude/agents/`).
2. Delegate by referencing the subagent name in your prompt or via the UI agent picker.
