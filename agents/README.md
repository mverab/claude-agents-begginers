# agents/

Curated, traditional agents for advanced users (e.g., code-refactorer, content-writer, frontend-designer, etc.).

AGENTS.md compatibility:
- These files are plain Markdown agents that work with any coding provider supporting the AGENTS.md standard.
- Agents read the nearest `AGENTS.md` (closest wins). See the root `AGENTS.md` for repo-wide guidance.
- Providers (non-exhaustive): Cursor, Aider, GitHub Copilot’s coding agent, Zed, Google Gemini CLI, RooCode, Factory, Amp, Ona, Phoenix, VS Code (project AI rules), Warp, Semgrep, Devin.
- Learn more: https://agents.md/

Install (copy-only):
```bash
# Global
mkdir -p ~/.claude/agents && cp agents/*.md ~/.claude/agents/
# Project-scoped
mkdir -p .claude/agents && cp agents/*.md .claude/agents/