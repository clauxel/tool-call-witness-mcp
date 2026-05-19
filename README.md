# ToolCall Witness MCP

A witness layer for AI agent tool calls.

Paid remote MCP for agent tool-call receipts, approval evidence, arguments redaction, result summaries, and review exports.

## Public Endpoints

- Website: https://toolcallwitness.clauxel.com/?utm_source=github&utm_medium=directory&utm_campaign=sbl202605
- MCP endpoint: https://toolcallwitness.clauxel.com/mcp
- Server card: https://toolcallwitness.clauxel.com/server-card.json
- Registry name: `com.clauxel.toolcallwitness/toolcallwitness-mcp`

## Access

This is a paid hosted remote MCP. Production calls require a bearer token issued from the product website.

```http
Authorization: Bearer <token>
```

Unauthenticated browser visits to `/mcp` return a clear JSON error instead of internal details.

## Tools

- `create_witness_receipt`
- `check_approval_rule`
- `summarize_risk_timeline`
- `export_audit_receipt`

## Quick Start

1. Open the website and choose a plan.
2. Create or request an API token.
3. Add the endpoint to an MCP client that supports Streamable HTTP remote servers.
4. Send JSON-RPC requests with the bearer token.

## Useful Links

- Product page: https://toolcallwitness.clauxel.com/?utm_source=github&utm_medium=directory&utm_campaign=sbl202605
- Pricing: https://toolcallwitness.clauxel.com/?utm_source=github&utm_medium=directory&utm_campaign=sbl202605#pricing
- Server card: https://toolcallwitness.clauxel.com/server-card.json
- MCP endpoint: https://toolcallwitness.clauxel.com/mcp

## Status

This repository is a public documentation and directory-submission reference for the hosted service. It does not contain the private production source code.
