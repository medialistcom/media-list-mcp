# Media List MCP Server

Find journalists, editors, TV and radio producers, podcast hosts and creators to pitch, by beat, outlet and location, right from your AI assistant.

This is the hosted MCP server for [Media List](https://medialist.com). There is nothing to install. Point your MCP client at the URL below and add your Media List API key.

## Connect

- **URL:** `https://medialist.com/mcp`
- **Transport:** Streamable HTTP
- **Auth:** your Media List API key, sent as `Authorization: Bearer <key>` or `X-Api-Key: <key>`

API keys are available on paid plans. Request one at [medialist.com/developers](https://medialist.com/developers).

### Example client config

```json
{
  "mcpServers": {
    "media-list": {
      "type": "http",
      "url": "https://medialist.com/mcp",
      "headers": { "Authorization": "Bearer YOUR_MEDIA_LIST_API_KEY" }
    }
  }
}
```

## Tools

All tools are read-only.

| Tool | What it does |
| --- | --- |
| `search_contacts` | Search media contacts by keyword, beat, media type and location |
| `get_contact` | Full profile for one contact |
| `search_outlets` | Find newspapers, magazines, TV and radio stations, sites and podcasts |
| `get_filter_values` | Valid values for the search filters |
| `list_lists` | Your saved lists |
| `get_list` | One saved list and its contacts |
| `list_campaigns` | Your email campaigns |
| `get_campaign` | One campaign with its status and counts |
| `get_account` | Your plan and limits |

## Also listed on

- [Official MCP Registry](https://registry.modelcontextprotocol.io/v0.1/servers?search=com.medialist) as `com.medialist/media-list`
- [Smithery](https://smithery.ai/servers/medialist/media-list)

## Links

- Website: [medialist.com](https://medialist.com)
- Pricing: [medialist.com/pricing](https://medialist.com/pricing)
