# Awesome Public Datasets – Government (Meta: EuroStat)

Meta entry pointing to Eurostat’s main public database, a comprehensive source of official EU statistics, especially for economics, population, and related topics.

- **Name:** Awesome Public Datasets – Government (Meta: EuroStat)
- **Type:** Themed directory → Meta reference to Eurostat database
- **Source:** [Eurostat main database](http://ec.europa.eu/eurostat/data/database)
- **Category:** Themed directories
- **Tags:** datasets, economics, statistics
- **Brand:** awesome-data

---

## Description

Eurostat’s main database provides multi-dimensional datasets of official European Union statistics. It covers a wide range of policy-relevant domains (such as economics, population, trade, and more) and allows users to explore, customise, and download data in multiple formats.

This entry in Awesome Public Datasets serves as an index link to that database rather than hosting data itself.

---

## Features

### Dataset Structure & Coverage
- **Detailed datasets**
  - Contains all publicly available Eurostat data.
  - Organised as multi-dimensional datasets (multiple variables and indicators).
- **Selected datasets**
  - Curated subset of Eurostat data with fewer indicators and variables.
  - Presented in 2- or 3-dimensional tables.
- **EU policies branch**
  - Datasets organised according to specific EU policy areas.
- **Cross-cutting branch**
  - Thematic selections from multiple sources and collections across topics.
- **Thematic organisation**
  - Both detailed and selected datasets are grouped into 9 high-level statistical themes.

### Access & Navigation
- **Data navigation tree**
  - Hierarchical browsing by themes and dataset types (detailed, selected, EU policies, cross-cutting).
- **Search by keyword**
  - Find datasets through a keyword-based search interface.

### Data Browser Tools
- **Interactive data browser**
  - Display and visualise data in table format.
  - Filter and subset dimensions (e.g., time, geography, indicators).
  - Create customised dataset views.
  - Save bookmarks for frequent views.
  - Download data in multiple formats.
  - Access online user help for detailed guidance.

### Download & Bulk Access
- **Multiple download formats**
  - All datasets can be downloaded in different machine-readable formats.
- **Dataset compression**
  - Download entire datasets in tab-separated values (TSV) format.
- **Bulk download and code lists**
  - Complete code lists (dictionaries) available under a dedicated bulk download “code lists” tab.

### Update Frequency
- **Twice-daily updates**
  - Data in the navigation tree are updated at **11:00** and **23:00** Central European Time (CET).

### Metadata & Documentation
- **Metadata access**
  - Explanatory texts and summary information about indicators and data collections.
- **Coding conventions**
  - `0` = real zero.
  - `0n` = less than half of the unit used and different from real zero.
- **Special value**
  - `:` = not available (used instead of a numeric value).

### Data Flags & Quality Annotations
As of 27 January 2025, flags are split into two code lists: **Obs_status** (observation status) and **Conf_status** (confidentiality status), aligned with SDMX usage.

**Observation status (Obs_status)**
- `b` – break in time series
- `d` – definition differs (see metadata)
- `e` – estimated
- `f` – forecast
- `i` – value imputed by Eurostat or other receiving agencies
- `m` – missing value, data cannot exist
- `n` – not significant
- `p` – provisional
- `u` – low reliability

**Confidentiality status (Conf_status)**
- `C` – confidential
- `N` – not for publication
- `P` – information under non-statistical secrecy arrangements

**Changes to previous codes**
- `s` (Eurostat estimate) → `i` (value imputed by Eurostat or other receiving agencies)
- `z` (not applicable) → `m` (missing value, data cannot exist)
- `c` (confidential) → `C` (confidential), now moved to the **Conf_status** code list

### Thematic Extras
- **COMEXT database** integration
  - Dedicated database containing data on international trade and production of goods, accessible via the same environment.

---

## Intended Use Cases
- Accessing official EU statistics for research, analysis, and policy evaluation.
- Building reproducible analyses using documented codes, flags, and metadata.
- Linking to Eurostat data from other “awesome datasets” style collections.

---

## Pricing

- **Cost:** Access to the Eurostat database and its public datasets is free of charge (no pricing tiers mentioned).

---

## Logo & Branding
- **Brand:** awesome-data
- **Brand logo URL:** `/awesome-data/logo.png`