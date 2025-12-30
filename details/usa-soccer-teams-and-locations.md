# USA Soccer Teams and Locations

An open dataset and repository listing USA soccer teams and their locations across MLS, NWSL, and USL, curated in the Awesome Public Datasets sports section.

## Overview

- **Type:** Open dataset / repository
- **Leagues covered:** Major League Soccer (MLS), National Women’s Soccer League (NWSL), United Soccer League (USL)
- **Focus:** Team locations, mapping, and related metadata for U.S. soccer clubs
- **Format:** CSV and GeoJSON files, plus web map visualizations
- **Source:** [GitHub – gavinr/usa-soccer](https://github.com/gavinr/usa-soccer)

## Features

- **League-specific datasets**
  - `mls.csv` and `mls.geojson` for MLS teams
  - `nwsl.csv` and `nwsl.geojson` for NWSL teams
  - `usl.csv` and `usl.geojson` for USL teams
- **Geospatial data**
  - Team locations provided as point data suitable for mapping
  - GeoJSON files ready for use in web mapping libraries and GIS tools
- **Map visualizations**
  - MLS logos map
  - NWSL logos map
  - USL logos map
  - Combined “All teams (points)” map showing all leagues together
  - Publicly accessible web maps at `https://maps.gavinr.com/usa-soccer` (with league-specific query parameters like `?nwsl` and `?usl`)
- **Image assets**
  - Preview images for MLS, NWSL, USL, and combined teams maps stored in the `images` directory
- **GIS compatibility**
  - Direct integration options for ArcGIS via ArcGIS Online items and maps tagged with `usa` and `soccer` by the dataset author
  - Data formats compatible with common GIS tools and workflows
- **Programmatic access**
  - CDN-hosted, versioned CSV files via jsDelivr, e.g.:
    - `https://cdn.jsdelivr.net/gh/gavinr/usa-soccer@master/mls.csv`
  - Similar URLs available for other leagues and formats (CSV/GeoJSON)
- **Repository structure**
  - `scripts` directory for data processing or generation scripts (for users who want to reproduce or extend the datasets)
  - `.github` configuration for repository meta and automation (not required for data use but available for contributors)
- **Documentation and references**
  - README-based overview of maps and data
  - Additional details and context at: [gavinr.com/maps/usa-soccer](https://gavinr.com/maps/usa-soccer/)

## Data Formats

- **CSV**
  - Tabular team data suitable for spreadsheets, data analysis, and import into BI tools.
- **GeoJSON**
  - Spatial point layers for each league, usable in web maps (Leaflet, Mapbox GL, etc.) and desktop GIS.

## Integrations & Usage

- **Web mapping**: Use GeoJSON endpoints directly in web mapping applications.
- **GIS platforms**: Load GeoJSON/CSV into ArcGIS (with pre-published ArcGIS Online items available) or other GIS software.
- **Data analysis**: Combine CSVs for cross-league comparison, spatial analysis, or sports analytics.

## Category

- **Category:** Datasets
- **Tags:** datasets, sports, GIS

## Pricing

- No pricing information is provided in the source content. The project is hosted on GitHub and appears to be an open dataset; refer to the repository’s LICENSE file for usage rights and conditions.
