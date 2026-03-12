# Relevance AI MCP Setup

## Prerequisites

- A Relevance AI account at [app.relevanceai.com](https://app.relevanceai.com)

## Remote MCP Server

```
https://mcp.relevanceai.com/
```

Transport: Streamable HTTP. No local installation required.

## Setup by tool

### OpenAI Codex

```bash
codex mcp add relevance-ai --url https://mcp.relevanceai.com/
codex mcp login relevance-ai
```

Restart Codex after login.

### Other tools

Add `https://mcp.relevanceai.com/` as a Streamable HTTP MCP server in your tool's MCP configuration. Authenticate with your Relevance AI API key when prompted.

## Verification

After setup, verify the connection works:

1. Run `relevance-ai:relevance_list_agents` — should return your project's agents (or an empty list for new projects).
2. Run `relevance-ai:relevance_list_tools` — should return your project's tools.
