# AGENTS.md — guided-agents

Focused guidance for coding agents working specifically with the 4-step guided flow.

## Scope
This folder contains four self-contained Claude agents designed to onboard beginners:
1. `agent-idea-guide.md` — Discover/refine the agent idea.
2. `agent-builder.md` — Turn the refined idea into a working agent.
3. `agent-installer.md` — Install the agent globally or per-project.
4. `agent-tester.md` — Validate and optimize the agent.

## Install (copy-only)
Global install (recommended):
```bash
mkdir -p ~/.claude/agents
cp guided-agents/*.md ~/.claude/agents/
```

Project-scoped install (specialized use):
```bash
mkdir -p .claude/agents
cp guided-agents/*.md .claude/agents/
```

## How to use in Claude Code
- Start with: “I want to use the agent-idea-guide to create my first agent.”
- Follow the handoff: Idea → Build → Install → Test.
- Each agent is optimized to explain the next step and keep users unblocked.

## Quick validation steps
- Idea check: “Use agent-idea-guide to define a meeting notes summarizer.”
- Build check: “Use agent-builder to create the summarizer agent with examples.”
- Install check: “Use agent-installer to install the agent globally.”
- Test check: “Use agent-tester to run a 5-minute validation.”

## Human-in-the-loop (HITL)
When file operations occur, request confirmation before:
- Overwriting existing agent files.
- Choosing global vs project install.
- Deleting or moving existing files.

If a conflict occurs, create a timestamped backup: `*.bak-YYYYMMDD-HHMMSS`.

## Editing conventions
- Agents use YAML front matter: `name`, `description`, `color`.
- Keep language clear, actionable, and beginner-friendly.
- Prefer iterative improvements over large rewrites.

## Uninstall
Global:
```bash
rm -f ~/.claude/agents/agent-idea-guide.md \
      ~/.claude/agents/agent-builder.md \
      ~/.claude/agents/agent-installer.md \
      ~/.claude/agents/agent-tester.md
```
Project:
```bash
rm -f .claude/agents/agent-idea-guide.md \
      .claude/agents/agent-builder.md \
      .claude/agents/agent-installer.md \
      .claude/agents/agent-tester.md
```

## Notes for maintainers
- Keep this guide lean and practical; avoid over-engineering.
- If adding new guided steps, update the list and validation flow accordingly.
