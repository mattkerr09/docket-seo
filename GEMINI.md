# Docket SEO tools

Five read-only tools check public web pages. Each takes a page address (https:// is assumed if left out).

- `check_page_seo`: a score out of 100, problems by area and the most serious problem with its fix, for one page.
- `check_ai_crawlers`: which AI crawlers the site's robots.txt allows for that path, and the rule that decides.
- `trace_redirects`: each redirect hop with its status code, flagging loops and chains.
- `check_http_headers`: the final status and the search and security headers, with a verdict on each.
- `preview_search_snippet`: where a title and description would be cut off in a search result. Takes a title and an optional description; fetches nothing.

Use them when the user asks about a page's SEO, robots.txt, redirects, headers or how a title will look in search results.
