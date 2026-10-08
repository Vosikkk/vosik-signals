# Google Search Console MCP

**Endpoint:** `https://gsc.vosiksignals.win/mcp`

The hosted GSC connector provides read-only access to Search Console data through MCP.

## Examples

- List accessible Search Console properties.
- Show daily search performance.
- Analyze queries and pages.
- Inspect the indexing status of a URL.
- Compare performance for different date ranges where supported.

Some reports may be incomplete or limited by Google's API coverage. Do not interpret absent rows as proof of zero traffic.

## Permissions

Google OAuth scope: `https://www.googleapis.com/auth/webmasters.readonly`

The connector uses read-only access. You must have permission to view the Search Console property.

## Connection

Follow [Getting started](getting-started.md), using the GSC endpoint above.
