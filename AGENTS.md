# AGENTS.md

A lean, predictable guide for coding agents to work with this repository.
This project provides a 4-step, beginner-friendly flow to create your first Claude agent without prior technical expertise.

## Project overview
- Goal: Help users go from idea → working Claude agent with minimal friction.
- Core assets are plain Markdown agent definitions used by Claude Code.
- No build or runtime dependencies; everything is file-based and portable.

## Relevant locations
- `guided-agents/` — The guided 4-step flow:
  - `agent-idea-guide.md`
  - `agent-builder.md`
  - `agent-installer.md`
  - `agent-tester.md`
- `agents/` — Curated, traditional agents for advanced users (e.g., code-refactorer, content-writer, etc.).
- Install locations for Claude Code:
  - Global: `~/.claude/agents/`
  - Project: `.claude/agents/` (relative to repo root)

## Quick setup (copy-only)
Global installation (recommended):
```bash
mkdir -p ~/.claude/agents
cp guided-agents/*.md ~/.claude/agents/
# Optionally also install the advanced agents
# cp agents/*.md ~/.claude/agents/
```

Project-scoped installation (for specialized agents):
```bash
mkdir -p .claude/agents
cp guided-agents/*.md .claude/agents/
# Optionally also install the advanced agents
# cp agents/*.md .claude/agents/
```

No other setup is required.

## How to use (Claude Code)
1) Open Claude Code in your IDE.
2) Start with: “I want to use the agent-idea-guide to create my first agent.”
3) Follow the guided sequence:
   - Idea → Build → Install → Test
4) The agents are designed to hand off to the next step automatically.

## Minimal testing instructions
- Activation check: “Use agent-idea-guide to help me define an email writing assistant.”
- Build: “Use agent-builder to create the agent we just defined.”
- Install: “Use agent-installer to install the agent globally.”
- Test: “Use agent-tester to run quick validation on the new agent.”

## Safety & HITL (Human-in-the-loop)
When automating operations that write or move files, agents should:
- Ask before overwriting an existing file.
- Create a timestamped backup if a collision occurs, e.g. `my-agent.md.bak-YYYYMMDD-HHMMSS`.
- Ask whether to install globally (`~/.claude/agents/`) or project-scoped (`.claude/agents/`).
- Confirm success and show the final path.

## Editing conventions for agent files
- Each agent is a single `.md` file with YAML front matter and body.
  - Front matter keys used in this repo: `name`, `description`, `color`.
  - Body contains the operative instructions and examples.
- Keep instructions clear, actionable, and scoped.
- Prefer small, maintainable changes over sweeping rewrites.

## Nested AGENTS.md
This repository also includes a nested `guided-agents/AGENTS.md` with focused instructions for the 4-step guided flow. Agents should prefer the closest `AGENTS.md` to the working directory.

## Uninstall / cleanup
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

## Notes
- This repo intentionally avoids over-engineering. Favor simple, 100% results-driven steps.
- If you need details specific to the guided flow, see `guided-agents/AGENTS.md`.
