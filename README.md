# Murkuz for Cursor

Murkuz is an SEO and content platform. This plugin connects Cursor to the hosted Murkuz MCP server (OAuth sign-in) so you can pull Search Console data, find quick wins and content decay, audit pages, and write or edit articles.

## Install

Add this plugin from Cursor Directory, or add the server by hand to your `mcp.json`:

```json
{
  "mcpServers": {
    "murkuz": {
      "url": "https://murkuz.com/mcp"
    }
  }
}
```

Cursor opens a sign-in page the first time a tool is used. No API key is stored in this repository.

## Contents

- `mcp.json`: the remote MCP server definition
- `skills/seo-workflow/SKILL.md`: guidance for the agent

Docs: https://murkuz.com/integrations/mcp

Maintained by [Ertiqah LLC](https://ertiqah.com). Licence: MIT.
