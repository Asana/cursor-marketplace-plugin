# Asana Plugin for Cursor

Manage your Asana tasks, projects, and portfolios directly from Cursor — no context switching required.

## What this plugin does

- Connects Cursor to the [Asana MCP server](https://developers.asana.com/docs/mcp)
- Gives the Cursor agent skills for setting up and using the Asana integration
- Adds guardrails to prevent accidental destructive actions

## Prerequisites

You need an Asana account and a registered Asana OAuth app.

1. Go to https://app.asana.com/0/my-apps
2. Create a new app
3. Add `cursor://anysphere.cursor-mcp/oauth/callback` as a redirect URI
4. Copy your **Client ID** and **Client Secret**

## Setup

Add these to your shell profile (`~/.zshrc`, `~/.bashrc`, etc.):

```bash
export ASANA_CLIENT_ID="your_client_id"
export ASANA_CLIENT_SECRET="your_client_secret"
```

Then restart Cursor. The agent will guide you through the rest.

## Install

Install from the [Cursor Marketplace](https://cursor.com/marketplace) — search for "Asana".

## Links

- [Asana MCP documentation](https://developers.asana.com/docs/connecting-mcp-clients-to-asanas-v2-server)
- [Asana Developer Console](https://app.asana.com/0/my-apps)
- [Asana API reference](https://developers.asana.com/reference)

## License

MIT
