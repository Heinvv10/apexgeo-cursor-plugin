# ApexGEO plugin for Cursor

Connect your ApexGEO account to Cursor to check how AI answers mention your brands and competitors, read recent mentions, and pull prioritised recommendations, right from your editor.

## What it does

This plugin adds the ApexGEO remote MCP server (`https://apexgeo.app/api/v1/mcp`) to Cursor. With it you can:

- list your brands
- get an AI-visibility summary per brand
- read recent mentions
- list and open recommendations
- check your search-data connections

Example prompts:

- "List my ApexGEO brands"
- "Give me the AI visibility summary for my first brand"
- "Show recent mentions"
- "What are the top recommendations?"

## Sign-in

The server uses OAuth (dynamic client registration with PKCE). The first time Cursor calls it, you are asked to sign in with your ApexGEO account and approve access (scopes `mcp:read` and `mcp:write`). No API key or token is stored in this plugin.

The plugin is free. It works on every ApexGEO plan, including the free tier; some data depends on your plan.

## Install locally

1. Copy this folder to `~/.cursor/plugins/local/apexgeo`.
2. Restart Cursor, or run **Developer: Reload Window**.
3. Open **Customize** and confirm the `apexgeo` MCP server is listed.

## Privacy and terms

- Privacy: https://apexgeo.app/privacy
- Terms: https://apexgeo.app/terms

## Support

support@apexgeo.app

Built by ApexGEO (Brightsphere Technologies, South Africa).

## Licence

MIT, see [LICENSE](LICENSE).
