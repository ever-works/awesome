# awesome-go-repo-stats

**Category:** Meta-directories  
**Brand:** emanuelef  
**Source:** https://github.com/emanuelef/awesome-go-repo-stats

## Overview
`awesome-go-repo-stats` is an open-source GitHub project that collects, analyzes, and exposes daily updated statistics for repositories listed in the `awesome-go` list. It acts as a meta-resource on top of the existing Awesome Go directory, providing data and analytics about listed Go repositories.

## Features
- **Daily updated statistics** for repositories included in the `awesome-go` list.
- **Data export files** in the repository root, including:
  - `analysis-latest.csv` – latest aggregated analysis of Awesome Go repositories.
  - `dep-repo-latest.csv` – dependency-related data for repositories.
  - `commits-history-30d.json` – commit activity history for the last 30 days.
  - `stars-history-30d.json` – stars history for the last 30 days.
  - `last-update.txt` – timestamp or marker of the last data update.
- **Go-based tooling** (`main.go`, `go.mod`, `go.sum`) to fetch and process GitHub repository data.
- **Website frontend** under the `website` directory to present and browse collected statistics.
- **OpenTelemetry instrumentation** (under `otel_instrumentation`) for observability of the data collection and processing pipeline.
- **GitHub workflow configuration** in `.github` for automated data updates and project CI/CD tasks.

## Use Cases
- Analyzing trends (stars, commits) across Awesome Go repositories.
- Identifying active or inactive projects within the Awesome Go list.
- Building additional tools, dashboards, or visualizations on top of the exported CSV/JSON data.
- Researching ecosystem health and activity in the Go open-source community.

## Pricing
- Not applicable – `awesome-go-repo-stats` is an open-source GitHub project (no pricing plans listed).