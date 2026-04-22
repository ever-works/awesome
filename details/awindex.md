## Overview

awindex reads a YAML configuration file specifying sources, downloads and caches data, and generates a static website with a Pagefind faceted search interface in the output directory. It also produces a SQLite database of records for inspection or custom use with tools like Datasette.

## Features

- **Source Ingestion**: Supports Awesome Lists (markdown parsing), public Zotero collections/groups, Zenodo communities, local JSONL files.
- **Search Interface**: Static HTML/JS using Pagefind for full-text and faceted search.
- **Data Export**: Generates `records.db` SQLite database and JSONL exports.
- **Caching**: Downloads and stores source data locally for reproducibility.
- **Customization**: Configurable site title, homepage, description; per-source name, homepage, description.

## Installation

Requires Python 3.11+.

```bash
pip install git+https://github.com/digipres/awesome-indexer@main
```

Or with uv:

```bash
uvx --from git+https://github.com/digipres/awesome-indexer@main awindex -c config.yaml -o ./index
```

## Configuration

Example `config.yaml`:

```yaml
title: "My Awesome Index Title"
homepage: https://my.website/page-about-this-index
description: "A brief description about this index and what's in it."
sources:
  - name: "Awesome Digital Preservation"
    homepage: "https://github.com/digipres/awesome-digital-preservation/"
    type: awesome-list
    url: "https://raw.githubusercontent.com/digipres/awesome-digital-preservation/refs/heads/main/README.md"
```

### Source Types

- **awesome-list**:
  - `url`: Markdown source (required)
  - `view_url`: Web view for line linking (optional)

- **zotero**:
  - `library_type`: 'user' or 'group' (required)
  - `library_id`: Numeric ID (required)
  - `collection_id`: Optional subcollection key
  - `api_key`: Optional for private access

- **zenodo**:
  - `community`: Identifier e.g. 'digital-preservation' (required)

- **jsonl**:
  - `file`: Local JSONL path (required)

## Usage

Run: `awindex -c config.yaml -o ./index`

Serve locally: `cd index && python -m http.server 8080`

Deploy to GitHub Pages, Netlify, etc.

Inspect DB: `uvx datasette serve index/records.db --metadata datasette-metadata.json`

## GitHub Actions

Example workflow using uv to build index.

## Development

Requires NodeJS (for Pagefind). Uses Jinja2 templating and Bootstrap 5.

Install editable: `pip install -e .`

## Pricing

Free and open-source (MIT license implied by GitHub repo).