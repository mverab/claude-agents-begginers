# guided-agents/

Minimal, results-driven 4-step flow for beginners:
- agent-idea-guide → agent-builder → agent-installer → agent-tester

AGENTS.md compatibility:
- This folder includes a local `AGENTS.md` so coding agents that support the AGENTS.md standard can work here directly (nearest file wins).
- Works with providers like Cursor, Aider, GitHub Copilot’s coding agent, Zed, Google Gemini CLI, RooCode, Factory, Amp, Ona, Phoenix, VS Code (project AI rules), Warp, Semgrep, Devin.
- Learn more: https://agents.md/

Install (copy-only):
```bash
# Global (recommended)
mkdir -p ~/.claude/agents && cp guided-agents/*.md ~/.claude/agents/
# Project-scoped
mkdir -p .claude/agents && cp guided-agents/*.md .claude/agents/