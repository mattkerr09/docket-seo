# Docket SEO for Gemini CLI

Free, read-only SEO checks of any public web page, as a Gemini CLI extension. It connects to the remote MCP server at
`https://mcp.docketseo.app/mcp`; nothing runs on your computer and there is no account or key.

```
gemini extensions install https://github.com/mattkerr09/docket-seo
```

Then ask, for example:

- "Check docketseo.app/pricing/ for SEO problems and tell me what to fix first."
- "Which AI crawlers can read example.com?"
- "Trace the redirects from http://example.com and check its security headers."
- "Will this title get cut off in Google: 'Emergency plumber in Grand Rapids, open 24 hours a day'?"

## Tools

| Tool | What it does |
|---|---|
| `check_page_seo` | A score out of 100, problems by area and the most serious problem with its fix, for one page |
| `check_ai_crawlers` | Which of 22 AI crawlers the site's robots.txt allows, and the rule that decides |
| `trace_redirects` | Every redirect hop with its HTTP status code |
| `check_http_headers` | The final status and the headers that matter for search and security |
| `preview_search_snippet` | Where a search result would cut off a title and description (fetches nothing) |

All five are read-only. What the server receives and keeps is on the privacy page:
https://docketseo.app/legal/privacy/ (the server keeps nothing about the sites checked).

Made by Kerr & Company LLC, the makers of Docket SEO (https://docketseo.app). Support: support@docketseo.app.
The same server is also listed in Claude's connector directory and works in any MCP client: https://docketseo.app/ai-assistants/
