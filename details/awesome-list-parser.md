## Overview

One source of truth for any GitHub awesome list. Turns awesome-* READMEs into consumable JSON for agents, dashboards, or pipelines.

## Features

- Fetches README via public GitHub API
- Parses standard markdown format: headers as categories, bulleted [name](url) - description entries
- Optional enrichment for github.com URLs: stars, forks, pushed_at, language, license, archived
- Configurable entry limit (1-1000)

## Input

| Field | Type | Default | Notes |
|-------|------|---------|-------|
| repo | string | `punkpeye/awesome-mcp-servers` | Awesome-list repo in owner/name form |
| enrich | boolean | `false` | Fetch GitHub metadata (slower, rate-limited) |
| limit | int | `200` | Cap parsed entries |
| githubToken | secret | `""` | PAT for high-volume enrichment |

## Output

Each record:
```json
{
  "category": "Databases / SQL",
  "name": "postgres-mcp",
  "url": "https://github.com/example/postgres-mcp",
  "description": "Read-only Postgres MCP server...",
  "github_repo": "example/postgres-mcp",
  "stars": 234,
  "forks": 12,
  "pushed_at": "2026-04-15T...",
  "language": "TypeScript",
  "license": "MIT",
  "archived": false
}
```
GitHub fields only if `enrich=true` and URL is GitHub.

## Use Cases

- Ingest curated directories for AI agents
- Audit for stale/archived repos
- Build meta-directories aggregating lists

## Limitations

- Standard markdown only (no tables/HTML/code fences)
- Non-GitHub URLs not enriched

## License

Apache-2.0