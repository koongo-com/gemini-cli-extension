# Koongo - Gemini CLI extension

Connect [Koongo](https://www.koongo.com) to Gemini and manage your product feeds and marketplace listings by chatting.

Koongo is an e-commerce solution that helps online merchants sell everywhere - connecting their product catalogue to 500+ sales channels through [product feed management](https://www.koongo.com/product-feed-management/) and [marketplace integration](https://www.koongo.com/sell-on-marketplaces/), all from one place.

This extension does not bundle any server code. It points Gemini at the hosted Koongo remote MCP server, so you can run your Koongo account in plain language: describe what you want and Gemini does it, showing each step before it commits.

## Install

```
gemini extensions install https://github.com/koongo-com/gemini-cli-extension
```

## What it connects to

- **Endpoint:** `https://mcp.koongo.com/mcp` (Streamable HTTP)
- **Authentication:** OAuth 2.0 (Dynamic Client Registration + PKCE), discovered automatically. On first use a browser opens - sign in with your Koongo account and approve access. The extension only ever accesses the projects your account owns.

## What you can do

- Browse and inspect your projects, feeds, marketplaces and ads
- Create and configure integrations for a wide range of sales and advertising channels - Google Shopping, Amazon, eBay, Kaufland, Bol, Zalando, Cdiscount and many more - through their step-by-step wizards
- Map channel attributes to your store fields, fixed values or rules
- Map your store categories to each channel's category tree
- Enrich products with new attributes (for example an AI-derived colour, material or size) and reuse them across feeds
- Build, filter, verify and export product feeds
- Track and manage marketplace orders and order connections

Built-in safety: anything that would publish products to a live channel is protected by a confirmation step, and you can set MANUAL mode and publish a single product as a dry run before releasing the rest.

## Example prompts

- "Create a Google Shopping feed for my store."
- "Add an Amazon marketplace integration and walk me through the setup."
- "Map my store categories to Google's product taxonomy."
- "Build, verify and export my Kaufland feed, and show me any errors."
- "Show my marketplace orders from the last 7 days and sync the new ones."

## Requirements

A Koongo account with at least one project (your store connected and its catalogue imported). No admin or special role is required.

Don't have an account yet? [Create one here](https://my.koongo.com/customer/account/create/).

## Documentation

MCP for AI assistants: https://help.koongo.com/en/collections/19723673-mcp-for-ai-assistants

## Support

Help center: https://help.koongo.com

## Learn more

- Website: https://www.koongo.com
- Product feed management: https://www.koongo.com/product-feed-management/
- Sell on marketplaces: https://www.koongo.com/sell-on-marketplaces/
