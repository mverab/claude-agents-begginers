# Legacy Claude Agents 🔧

This directory contains the original Claude agents for advanced users who prefer direct agent usage without guided setup.

## Installation

### For Global Use (All Projects)
```bash
mkdir -p ~/.claude/agents
cp agents/*.md ~/.claude/agents/
```

### For Project-Specific Use
```bash
mkdir -p .claude/agents
cp agents/*.md .claude/agents/
```

## Available Legacy Agents

### 🔨 code-refactorer
**Code refactoring assistance**
- Analyzes code structure and suggests improvements
- Identifies code smells and anti-patterns
- Provides refactoring recommendations

### ✍️ content-writer
**Content writing assistance**
- Helps create engaging written content
- Adapts tone and style to different audiences
- Provides editing and improvement suggestions

### 🎨 frontend-designer
**Frontend design assistance**
- UI/UX design guidance and best practices
- Component design and layout suggestions
- Accessibility and responsive design advice

### 📋 prd-writer
**Product requirement document writing**
- Structures and writes comprehensive PRDs
- Defines features, user stories, and acceptance criteria
- Ensures clarity and completeness in requirements

### 📊 project-task-planner
**Project planning and task breakdown**
- Breaks down complex projects into manageable tasks
- Creates realistic timelines and milestones
- Identifies dependencies and potential blockers

### 🔒 security-auditor
**Security audit assistance**
- Reviews code for security vulnerabilities
- Suggests security best practices
- Identifies potential attack vectors

### 💫 vibe-coding-coach
**Coding guidance and coaching**
- Translates user visions into working applications
- Provides mentorship and learning guidance
- Focuses on user experience and best practices

## Usage

Once installed, Claude Code will automatically detect and use these agents when appropriate for your tasks. These agents are designed for users who:

- Have experience with Claude Code
- Prefer direct agent interaction
- Want specific, focused assistance
- Don't need guided setup

## For Beginners

If you're new to Claude agents, we recommend starting with our **guided system** instead:

👉 **[Try the Guided Agents System](../guided-agents/README.md)**

The guided system provides:
- Step-by-step agent creation
- No technical setup required
- Built-in testing and optimization
- Beginner-friendly experience

## Advanced Usage

These legacy agents can be:
- **Combined** with other agents for complex workflows
- **Customized** by editing their markdown files
- **Extended** with additional capabilities
- **Integrated** into existing development processes

Ready to use these powerful agents? Install them and start building! 🚀
