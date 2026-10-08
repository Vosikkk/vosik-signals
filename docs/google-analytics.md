# Google Analytics 4 MCP

**Endpoint:** `https://ga4.vosiksignals.win/mcp`

The hosted GA4 connector provides read-only access to Google Analytics data through MCP.

## Examples

- List accessible Google Analytics accounts and properties.
- Report sessions and active users by date.
- Explore acquisition sources.
- Compare periods using available report tools.

Actual metrics, dimensions, and filters depend on the server's tools and Google Analytics API constraints.

## Permissions

Google OAuth scope: `https://www.googleapis.com/auth/analytics.readonly`

The GA4 OAuth application has passed Google's verification for this sensitive scope. The connector cannot modify GA4 resources using this permission.

## Connection

Follow [Getting started](getting-started.md). Choose a Google account with access to the GA4 property you want to analyze.

## More

See the [connector-specific GitHub repository](https://github.com/Vosikkk/google-analytics-mcp).
