# Vosik Signals

**Google Analytics 4 and Google Search Console for AI assistants, via MCP.**

Vosik Signals provides hosted, read-only Model Context Protocol (MCP) connectors for accessing Google Analytics and Search Console data from compatible AI clients.

No server installation is required. Connect to a remote MCP endpoint and authorize access to your Google account.

| Connector | What you can explore | Remote MCP endpoint |
| --- | --- | --- |
| **Google Analytics 4 (GA4)** | Traffic, users, acquisition, and analytics reports | `https://ga4.vosiksignals.win/mcp` |
| **Google Search Console (GSC)** | Search queries, pages, clicks, impressions, positions, and URL inspection | `https://gsc.vosiksignals.win/mcp` |

## Getting started

1. Choose the connector you need.
2. In an AI client supporting **remote Streamable HTTP MCP** and OAuth, add its endpoint.
3. Complete Google sign-in and consent.
4. Ask your assistant to list the Google Analytics properties or Search Console sites you can access.

See [Getting started](docs/getting-started.md) for details. The ChatGPT integration has been used with these servers; other clients may require compatibility testing.

## Example questions

**GA4**
- List my Google Analytics accounts and properties.
- Show sessions and active users by date for the last seven days.
- Compare traffic between two date ranges.

**GSC**
- List my Search Console properties.
- Show search clicks and impressions for the last 28 days.
- Which search queries lead to a specific page?
- Inspect a URL's indexing status.

Results depend on your Google account permissions, API availability, and the tools exposed by each connector.

## Documentation

- [Getting started](docs/getting-started.md)
- [Google Analytics 4](docs/google-analytics.md)
- [Google Search Console](docs/google-search-console.md)
- [Other MCP clients](docs/other-clients.md)
- [Security](SECURITY.md)
- [Changelog](CHANGELOG.md)

## Security and privacy

Both connectors use Google OAuth and request read-only API scopes. Access to data is limited by the permissions granted to the signed-in Google account. The GA4 OAuth application has completed Google's verification for the `analytics.readonly` scope.

See the [Privacy Policy](https://vosiksignals.win/privacy) for details about credentials, processing, retention, and deletion. Never share tokens or private reports in public issues.

## Project structure

This is the **public documentation and support repository** for Vosik Signals. The production Cloudflare Workers and their implementation code are maintained separately and are **not open source** through this repository.

Connector-specific GitHub entry point: [Google Analytics MCP](https://github.com/Vosikkk/google-analytics-mcp).

## Feedback

Use [GitHub Issues](https://github.com/Vosikkk/vosik-signals/issues) for bugs, feature requests, and compatibility feedback. Please redact sensitive data.

Website: https://vosiksignals.win
