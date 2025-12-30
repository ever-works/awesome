# IMDb Database Interfaces

**URL:** https://www.imdb.com/interfaces  
**Category:** Themed Directories  
**Tags:** datasets, media, recommendation

## Overview

IMDb Database Interfaces provide machine-readable, plain-text access to subsets of the Internet Movie Database for personal and non-commercial use. The data covers movies, TV, ratings, and people, and is widely used as a benchmark dataset in recommendation systems and machine learning research.

Data is distributed as gzipped, UTF-8, tab-separated values (TSV) files, refreshed daily and downloadable from:

- https://datasets.imdbws.com/

Use is governed by IMDb’s non-commercial licensing terms and copyright/license.

## Features

- **Non-commercial IMDb data access**
  - Subsets of IMDb data available for personal and non-commercial use.
  - Local copies may be held subject to IMDb terms and conditions.
  - Must comply with IMDb non-commercial licensing and copyright policies.

- **Data refresh and availability**
  - Dataset files hosted at: https://datasets.imdbws.com/
  - Data is refreshed **daily**.

- **File format and encoding**
  - Each dataset is a separate file: `*.tsv.gz` (gzipped TSV).
  - UTF-8 character set.
  - First line contains column headers describing each field.
  - Missing or null values represented by `\N`.

- **Available datasets**
  - **`title.akas.tsv.gz`**
    - Alternate titles and related metadata for titles (e.g., localized titles / AKA information).
  - **`title.basics.tsv.gz`**
    - Core information about titles (e.g., movies, TV shows, etc.).
  - **`title.crew.tsv.gz`**
    - Crew information by title (e.g., directors, writers).
  - **`title.episode.tsv.gz`**
    - Episode-level information for episodic content.
  - **`title.principals.tsv.gz`**
    - Principal cast and crew for each title.
  - **`title.ratings.tsv.gz`**
    - User ratings for titles.
  - **`name.basics.tsv.gz`**
    - Person-level data (e.g., actors, directors, etc.).

- **Schema stability notice**
  - As of **March 18, 2024**, datasets are backed by a new data source.
  - No change in file **location** or **schema**.
  - Issues after this date can be reported to: **imdb-data-interest@imdb.com**.

- **Typical use cases (implied by description)**
  - Benchmark datasets for **recommendation systems**.
  - Research and experiments in **machine learning** and **information retrieval**.
  - Analytics on film/TV content, people, and ratings.

## Licensing & Usage

- Intended for **personal and non-commercial** use.
- Users must review and comply with:
  - Non-Commercial Licensing: (linked from page)
  - Copyright/License: (linked from page)

## Pricing

- No explicit pricing information is provided in the content. The described access is for **non-commercial** use under IMDb’s licensing terms; commercial licensing is not detailed on this page.
