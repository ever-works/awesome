# Awesome JSON Datasets

A curated, community-maintained directory of publicly available JSON datasets that do not require authentication. Useful for testing, learning, prototyping, and data-driven projects.

---

## Overview

- **Type:** Themed directory / curated list
- **Format:** GitHub repository (Markdown list of links)
- **Focus:** JSON datasets accessible over HTTP(S) without auth
- **Use cases:** API experimentation, demos, tutorials, sample apps, data analysis, QA/testing

---

## Features

### General Characteristics
- Curated list of JSON datasets from many public sources.
- All entries are accessible via HTTP(S) and return JSON.
- Datasets generally do **not** require authentication to access.
- Links point directly to JSON endpoints or API documentation for JSON responses.
- Organized by topic for easier discovery.
- Hosted and versioned on GitHub, allowing community contributions.

### Thematic Categories & Example Datasets

**Bitcoin**
- `Latest Block` – `https://blockchain.info/latestblock`
- `Unconfirmed Transactions` – `https://blockchain.info/unconfirmed-transactions?format=json`
- Additional suggestion: cryptocurrency price data via CoinMarketCap (`https://api.coinmarketcap.com/v1/ticker/`).

**Climate**
- US climate-related series from NOAA:
  - `US Annual Average Temperature and Anomaly` (1880–2015 vs. 1901–2000 average)
    - `https://www.ncdc.noaa.gov/cag/time-series/us/110/00/tavg/ytd/12/1895-2016.json?base_prd=true&begbaseyear=1901&endbaseyear=2000`
  - `Contiguous US Annual Precipitation` (1895–2015)
    - `https://www.ncdc.noaa.gov/cag/time-series/us/110/00/pcp/ytd/12/1895-2016.json?base_prd=true&begbaseyear=1901&endbaseyear=2000`

**Crime**
- `DATA.POLICE.UK` APIs:
  - Crimes at specific location and date:
    - `https://data.police.uk/api/crimes-at-location?date=2015-02&lat=52.629729&lng=-1.131592`
  - Street crime dates:
    - `https://data.police.uk/api/crimes-street-dates`
  - Neighbourhoods:
    - `https://data.police.uk/api/leicestershire/neighbourhoods`
  - List of police forces:
    - `https://data.police.uk/api/forces`
- `DATA.GOV` local crime data:
  - Chicago crime data (historical since 2001):
    - `https://data.cityofchicago.org/api/views/ijzp-q8t2/rows.json?accessType=DOWNLOAD`
  - Los Angeles crime data (historical since 2010):
    - `https://data.lacity.org/api/views/y8tr-7khq/rows.json?accessType=DOWNLOAD`

**Currency**
- `Exchange Rate API` – base endpoint and examples for live FX rates:
  - Site: `https://www.exchangerate-api.com`
  - Latest rates with base USD:
    - `https://api.exchangerate-api.com/v4/latest/USD`
  - Latest rates with base GBP:
    - `https://api.exchangerate-api.com/v4/latest/GBP`

**Food**
- FDA food enforcement data:
  - `https://api.fda.gov/food/enforcement.json`
- Open Food Facts product information (example product):
  - `https://world.openfoodfacts.org/api/v0/product/5060292302201.json`

**Gaming**
- Pokémon API:
  - Documentation (v2): `https://pokeapi.co/docsv2/`

**Additional Sections (listed in contents)**
*(These are section headings present in the repository; each contains multiple dataset links in the full list.)*
- GitHub API
- Government
- Historical Events
- HTTP
- NASA
- Nobel Prize
- Population
- GDP
- Reddit
- Travel
- TV Shows
- Movies
- Open Source Licenses
- More Awesome Lists

### Community & Maintenance
- Hosted on GitHub with:
  - **Contributing** guidelines for adding or updating datasets.
  - **License** information for the list itself.
- Part of the broader `awesome` ecosystem (referenced by the Awesome badge).

---

## Pricing

- Access to the **Awesome JSON Datasets** list is **free** (open GitHub repository).
- Individual datasets/APIs may have their own usage limits or terms, but the list itself does not impose pricing or subscription plans.

---

## Links

- **Main Directory:** https://github.com/jdorfman/awesome-json-datasets#readme
