# Digital Drywood Skills

A collection of portable AI agent skills following the [agentskills.io](https://agentskills.io) specification.

## Overview

This repository contains skills for AI coding assistants, designed to work across multiple platforms including:

- Claude Code
- VS Code Copilot
- Cursor
- Any agent supporting the agentskills.io standard

## Skills

| Skill | Description |
|-------|-------------|
| `go-best-practices` | Go idiomatic patterns, error handling, and best practices |
| `go-web-templui` | Go + Templ + HTMX web development with templUI components |
| `second-opinion` | Multi-perspective analysis for architectural decisions |
| `tailwind-best-practices` | Tailwind CSS v4 patterns and utility optimization |

## Installation

### Claude Code

```bash
/install github:digitaldrywood/skills
```

### VS Code Copilot

Add to your settings:

```json
{
  "github.copilot.chat.skills": [
    "github:digitaldrywood/skills"
  ]
}
```

### Cursor

Add the repository to your Cursor skills configuration.

## Specification

All skills in this repository conform to the [agentskills.io specification](https://agentskills.io/specification):

- SKILL.md files with YAML frontmatter
- Required fields: `name`, `description`
- Optional: `license`, `compatibility`, `metadata`
- Supporting content in `references/` directories
- Main SKILL.md files kept under 500 lines

## License

Apache-2.0
