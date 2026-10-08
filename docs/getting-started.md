# Getting started

Vosik Signals offers two hosted remote MCP servers:

- **GA4:** `https://ga4.vosiksignals.win/mcp`
- **GSC:** `https://gsc.vosiksignals.win/mcp`

## Connect

1. In your MCP-compatible AI client, add a **remote** MCP server using **Streamable HTTP**.
2. Paste the endpoint for the connector you want.
3. Complete the Google OAuth flow using an account with access to the relevant GA4 properties or Search Console sites.
4. Start by asking the assistant to list available properties/sites.

You can add both connectors independently. Each endpoint has its own authorization flow.

## First prompts

**GA4:** “List the Google Analytics accounts and properties I can access.”

**GSC:** “List the Search Console properties I can access.”

If a property is missing, check permissions on the Google account you authorized.

See [GA4](google-analytics.md), [GSC](google-search-console.md), and [Other clients](other-clients.md).

## Notes

Clients differ in support for remote OAuth and presentation of MCP tools. A client supporting MCP in general is not necessarily compatible with every remote OAuth server.
