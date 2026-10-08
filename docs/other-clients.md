# Using Vosik Signals with other MCP clients

Vosik Signals exposes remote **Streamable HTTP** MCP endpoints:

```text
https://ga4.vosiksignals.win/mcp
https://gsc.vosiksignals.win/mcp
```

In your client's remote MCP configuration, add one endpoint at a time and complete its Google OAuth authorization flow.

## Compatibility status

ChatGPT is the primary integration used during development. End-to-end compatibility with Claude, Cursor, and other clients has **not yet been confirmed**. Support depends on the client's remote MCP transport and OAuth implementation.

If you test a client, please open an issue with the client/version, whether OAuth completed, and whether listing properties worked. Never post credentials or private analytics data.
