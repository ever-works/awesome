# awesome-startups

**Category:** Themed Directories  
**Tags:** startups, business-tools, awesome-lists

A GitHub-hosted, automatically updated directory of the top 100 startups worldwide, plus country-specific startup lists, based on data from Startupranking.

---

## Overview

`awesome-startups` is an open-source curated list that aggregates startup rankings from [startupranking.com](http://startupranking.com). It maintains:

- A global list of the top 100 startups
- Per-country lists of startups
- A ranking-based structure that’s regenerated regularly using a PHP script and JSON data files

The project follows the broader `awesome-*` list convention and is designed as a reference resource for founders, researchers, and startup enthusiasts.

---

## Features

- **Global Top 100 List**  
  - Maintains a list of the top 100 startups worldwide.  
  - Rankings are sourced directly from Startupranking and ordered by rank.

- **Country-based Startup Lists**  
  - `countries/` directory contains per-country startup lists.  
  - Countries are sorted in descending order by the number of startups associated with each country.  
  - Within each country file, startups are sorted in ascending order of their rankings.

- **Automated Daily Updates**  
  - A PHP script (`fetch-countries.php` and `index.php`) fetches and processes the latest data from startupranking.com.  
  - Lists are regenerated on a daily basis to keep rankings current.  
  - README includes a `Last Updated On` timestamp indicating the last successful update.

- **Structured Data Source Handling**  
  - Uses `supported-countries.json` to track which countries are supported (i.e., have startups registered on Startupranking).  
  - Script logic “crunches” raw ranking data into structured lists used in the README and country files.

- **Open-source Repository Layout**  
  - `README.md` – main listing and documentation.  
  - `countries/` – country-wise startup listings.  
  - `supported-countries.json` – machine-readable list of supported countries.  
  - `pre-readme-content.txt` and `post-readme-content.txt` – template fragments to build the dynamic README.  
  - `LICENSE` – license file (open-source terms).  
  - `.gitignore` – standard Git configuration.

- **Dynamic README Generation**  
  - README is programmatically generated, combining template files with live data.  
  - Includes a contents section and a data freshness timestamp.

- **Inspired by `awesome-*` Ecosystem**  
  - Follows conventions of popular “awesome lists” (curated, topic-focused, GitHub-native).

---

## Data Source

- Primary data source: **[Startupranking](http://startupranking.com)**.  
- All rankings and country/startup associations are derived from Startupranking’s listings.

---

## Pricing

This is an open-source GitHub repository and directory list. There is no pricing or paid plan; usage and access are free, subject to the project’s LICENSE.