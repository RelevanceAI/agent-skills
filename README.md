# Relevance AI Agent Skills

[Agent Skills](https://agentskills.io) for managing AI agents, tools, and multi-agent workforces on [Relevance AI](https://relevanceai.com).

Works with any tool that supports the Agent Skills open standard — including Codex, Claude Code, Cursor, Gemini CLI, GitHub Copilot, and [many more](https://agentskills.io).

## Installation

### OpenAI Codex

```bash
git clone https://github.com/RelevanceAI/agent-skills ~/.agents/skills/relevance-ai
```

### Claude Code

```bash
git clone https://github.com/RelevanceAI/agent-skills ~/.claude/skills/relevance-ai
```

### Cursor / VS Code Copilot / Other tools

Clone into your tool's skills folder:

```bash
git clone https://github.com/RelevanceAI/agent-skills .agents/skills/relevance-ai
```

### MCP server only (any tool)

If your tool supports MCP but not Agent Skills, just add the remote MCP server directly:

```
https://mcp.relevanceai.com/
```

Transport: Streamable HTTP.

## What's included

```
SKILL.md                              — Main skill definition, workflows, and API rules
agents/openai.yaml                    — Agent interface config with MCP dependency
assets/                               — Icons (32x32 SVG + 256x256 PNG)
reference/
    ├── setup.md                      — MCP setup and verification
    ├── managing-relevance-agents/    — Creating agents, tools, triggers, troubleshooting
    ├── managing-relevance-tools/     — Building tools, transformations, patterns, OAuth
    ├── managing-relevance-workforces/— Multi-agent orchestration and debugging
    ├── managing-relevance-knowledge/ — Knowledge table operations
    ├── relevance-analytics/          — Usage analytics
    └── relevance-evals/              — Agent evaluations and testing
```

## Capabilities

- **Agents** — Create, configure, attach tools, trigger conversations, manage triggers
- **Tools** — Build custom workflows from 8000+ integrations, test and iterate
- **Workforces** — Orchestrate multi-agent pipelines with configurable handover patterns
- **Knowledge** — Data tables for agent memory, lead tracking, and research storage
- **Marketplace** — Browse and clone pre-built agent and tool solutions
