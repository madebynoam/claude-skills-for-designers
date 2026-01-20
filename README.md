# Claude Skills for Designers

**A toolkit for designers who work in code but don't live there.**

Most Claude Code skills assume you're a developer. These skills are different—they're designed for the designer's journey through a codebase: finding components, understanding design systems, making safe visual changes, and prototyping in real code without fear.

## Why This Exists

Designers increasingly need to work directly in code, but codebases are intimidating. These skills bridge the gap between "I have Figma" and "I need to ship this."

**Built for designers who:**
- Want to find where a component lives without grep wizardry
- Need to make a CSS tweak without breaking production
- Prototype new screens following existing patterns
- Audit design consistency across a codebase
- Feel confident navigating code, not just reading it

## Skills

### [component-detective](./skills/component-detective/)
**Find UI components from screenshots, route paths, or component names.**

The core designer superpower: "I see this button in the app... where's the code?" Give it a screenshot, and it finds the component. Works with React, Vue, Angular, and other component-based frameworks.

```
Input:  Screenshot of a pricing card
Output: PricingCard component location, styles, related files
```

### [workflow-mining](./skills/workflow-mining/)
**Turn productive sessions into reusable skills.**

At the end of a session, this skill analyzes what you did and suggests patterns worth automating. It's how these skills were born—and how you'll create your own.

```
Input:  "What patterns did I use today?"
Output: Suggested skills with value assessment and build complexity
```

### [session-reflect](./skills/session-reflect/)
**Capture learnings before they fade.**

A guided reflection for the end of a work session. Surfaces what you learned (technical and soft skills), how you feel, and creates a searchable record of growth over time.

```
Input:  End of a challenging session
Output: Structured reflection with learnings, feelings, and context
```

## Installation

These skills work with [Claude Code](https://claude.ai/code). To use them:

1. Clone this repo or download individual skill folders
2. Copy skills to `~/.claude/skills/`
3. Skills activate automatically when relevant

Or reference them directly:
```bash
# In Claude Code
"Use the component-detective skill to find where this screenshot lives"
```

## Philosophy

These skills embody a few principles:

1. **Reduce fear, increase confidence** — Codebases shouldn't be scary for designers
2. **Progressive disclosure** — Start simple, reveal complexity only when needed
3. **Screenshot-first** — Visual input is a designer's native language
4. **Learning loops** — Reflection builds lasting skills, not just task completion

## Coming Soon

- **visual-tweak** — Safe CSS changes with preview and easy revert
- **design-token-explorer** — Map the design system actually in use
- **feasibility-check** — "Can we build this?" analysis before designing
- **inconsistency-finder** — Audit for design debt across a codebase

## About

Created by [Noam Almosnino](https://noamalmos.com), a designer at Automattic exploring how AI tools can make codebases more accessible to designers.

These skills grew out of real daily work—navigating a large React codebase, making design changes, and reflecting on what worked. They're functional prototypes: code-based artifacts that define agentic workflows for Claude Code.

---

*"At the intersection of code and design"*
