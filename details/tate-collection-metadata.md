# Tate Collection metadata

## Overview
Tate Collection metadata is a GitHub-hosted dataset providing a snapshot (as of October 2014) of metadata for around 70,000 artworks and 3,500 associated artists from Tate and jointly owned works with the National Galleries of Scotland (ARTIST ROOMS). It is aimed at researchers and developers interested in museum and art collection data.

- **Type:** Open dataset / museum collection metadata
- **Source:** GitHub repository (`tategallery/collection`)
- **Scope:** ~70,000 artworks, ~3,500 artists
- **Status:** No longer actively maintained; last update October 2014
- **License:** Creative Commons CC0 (Public Domain) for metadata

## Features

### Dataset contents
- **Artworks metadata**
  - Metadata for approximately 70,000 artworks
  - Covers works owned or jointly owned by Tate
  - Includes works jointly owned with the National Galleries of Scotland via ARTIST ROOMS
  - Available as:
    - `artworks/` (JSON files organized in directories)
    - `artwork_data.csv` (tabular CSV export)

- **Artists metadata**
  - Metadata for around 3,500 associated artists
  - Available as:
    - `artists/` (JSON files organized in directories)
    - `artist_data.csv` (tabular CSV export)

### Data formats and structure
- **JSON format**
  - Richer, more detailed dataset
  - Organized via directory structure (e.g., `artists/`, `artworks/`, `processed/`)

- **CSV format**
  - `artist_data.csv` for artist-level information
  - `artwork_data.csv` for artwork-level information
  - Suitable for quick loading into analytical tools and spreadsheets

- **Processed data**
  - `processed/` directory for derived or cleaned versions of the data (as provided in the repository)

- **Additional repository files**
  - `README.md` with usage notes and examples
  - `LICENCE` with detailed CC0 license text
  - `.gitignore` and `bin/` directory for repository tooling/scripts (where present)

### Usage and licensing
- **License for metadata**
  - Released under **Creative Commons CC0 1.0 Public Domain Dedication**
  - Intended for unrestricted reuse, remixing, and redistribution of the metadata

- **Images**
  - Images are **not included** in this dataset
  - Image use is governed separately via Tate’s
    - Website copyright and permissions
    - Commercial image licensing services

- **Community and contributions**
  - GitHub Issues used for reporting data bugs or suggesting improvements
  - Pull requests invited for adding examples of projects using the data

### Maintenance status
- Dataset is a **fixed snapshot** as of **October 2014**
- Tate has **no plans to resume updating** this repository
- Kept online as a stable historical resource for researchers and developers

## Category
- Themed directories / datasets
- Focus: art, cultural heritage, museum collections

## Tags
- datasets
- art
- metadata

## Pricing
- **Free**: Metadata is available at no cost under the CC0 Public Domain license.
