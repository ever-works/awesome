# GitHub Collaboration Archive (GH Archive)

## Overview
GitHub Collaboration Archive (GH Archive) is a continuously updated archive of public GitHub events. It records and stores the public GitHub timeline and makes it accessible for large-scale analysis of developer activity, collaboration patterns, and repository events.

- **Type:** Dataset / public event archive
- **Category:** Datasets
- **Source:** https://www.gharchive.org/
- **Data domain:** Public GitHub events (commits, forks, issues, comments, membership changes, and more)

## Features

### Data Coverage & Content
- Records public GitHub timeline events from GitHub’s event stream.
- Supports 15+ official GitHub event types (e.g., pushes, forks, issue events, pull requests, comments, membership changes).
- Each archive file contains JSON-encoded events as returned by the GitHub API.
- Includes structured fields matching GitHub’s activity/event API response format.
- Provides a `payload` field with JSON-encoded activity details.
- Provides an `other` field containing remaining, less common fields.

### Data Access via HTTP Archives
- Events are aggregated into **hourly archive files**.
- Archives are available via simple HTTP endpoints (compatible with tools like `wget` or any HTTP client).
- Example access patterns:
  - Activity for a specific hour: `https://data.gharchive.org/2015-01-01-15.json.gz`
  - Activity for a specific day (all hours): `https://data.gharchive.org/2015-01-01-{0..23}.json.gz`
  - Activity for a full month (all days, all hours): `https://data.gharchive.org/2015-01-{01..31}-{0..23}.json.gz`
- Data is provided as compressed (`.json.gz`) JSON files for efficient download.
- Suitable for offline processing: custom scripts, ingestion into databases, or data pipelines.

### BigQuery Public Dataset Integration
- Entire archive is mirrored as a **public dataset on Google BigQuery**.
- Dataset is **automatically updated hourly** to stay in sync with new GitHub events.
- Enables **SQL-like querying** over the full event history.
- Supports fast, large-scale analysis (seconds to query across large time ranges, subject to BigQuery performance and quotas).

#### BigQuery Tables & Organization
- Multiple tables organized by year and finer-grained partitions, for example:
  - `2011`, `2012`, `2013`, `2014`, `2015`
  - `201501` (month-level granularity)
  - `20150101` (day-level granularity)
- Table wildcard functions can be used to query across multiple tables in one query (e.g., across multiple days or months).

#### BigQuery Schema
- Schema mirrors GitHub’s event API structure.
- Common activity fields are exposed as separate columns.
- `payload` column stores JSON-encoded activity details, which can be parsed using functions like `JSON_EXTRACT()`.
- `other` column stores additional, less common fields as a JSON string.

### Example Usage & Workflow
- Download raw hourly JSON archives for:
  - Custom aggregation scripts (e.g., in Ruby, Python, etc.).
  - Import into relational or NoSQL databases.
  - Feeding dashboards or analytics tools.
- Run BigQuery queries for:
  - Analyzing project popularity and activity over time.
  - Studying collaboration networks and social coding patterns.
  - Generating reports or feeds of trending repositories.

### Related Outputs / Reports
- Data powers external reporting products such as Changelog’s daily and weekly reports:
  - **Changelog Nightly**: daily email highlighting hot new GitHub repositories, built on GH Archive data.
  - **Changelog Weekly**: curated, less frequent digest leveraging the same underlying dataset.

### Openness & Community
- Project source code is available on GitHub: `igrigorik/gharchive.org`.
- Open to community contributions (e.g., adding research, visualizations, or projects built on GH Archive via pull requests).

## Pricing
- Access to the raw GH Archive HTTP data is not described as paid; it is presented as an open public archive.
- When using the Google BigQuery public dataset:
  - BigQuery provides **1 TB of data processed per month free of charge** (subject to Google Cloud’s own pricing and quotas).
  - Additional BigQuery usage beyond the free tier is billed by Google according to their BigQuery pricing (not set by GH Archive).

*(No distinct pricing plans or tiers specific to GH Archive itself are described in the provided content.)*