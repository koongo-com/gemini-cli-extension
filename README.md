# Koongo - Gemini CLI extension

Connect [Koongo](https://www.koongo.com) to Gemini as an MCP extension. Koongo is an e-commerce solution that helps online merchants sell everywhere - connecting their product catalogue to 500+ sales channels through product feed management and marketplace integration.

This extension does not bundle any server code. It points Gemini at the hosted Koongo remote MCP server so you can manage your product feeds, marketplace listings and orders in plain language.

## Install

```
gemini extensions install https://github.com/koongo-com/gemini-cli-extension
```

## What it connects to

- **Endpoint:** `https://mcp.koongo.com/mcp` (Streamable HTTP)
- **Auth:** OAuth 2.0 (Dynamic Client Registration + PKCE), discovered automatically. On first use a browser opens; sign in with your Koongo account and approve access.

## Requirements

A [Koongo account](https://www.koongo.com) with at least one project. The connector only ever accesses the projects your account owns.

## What you can do

- Browse projects, feeds, marketplaces and ads
- Create and configure sales / advertising channel integrations
- Map channel attributes and store categories
- Enrich products and build, filter, verify and export feeds
- Track and sync marketplace orders

## Documentation

https://help.koongo.com/en/collections/19723673-mcp-for-ai-assistants

## Support

support@koongo.com
