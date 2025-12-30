## Overview

The **Minneapolis Institute of Arts metadata** repository is a public GitHub project that exposes structured metadata for artworks in the Minneapolis Institute of Art (Mia) collection. It provides the same data used on Mia’s official collections website, but in bulk, developer‑friendly formats for analysis, research, and creative projects.

- **Type:** Open dataset / GitHub repository
- **Category:** Themed directories
- **Topics:** Art collections, cultural heritage, open data, JSON datasets
- **Source:** https://github.com/artsmia/collection

## Features

### Dataset Contents & Structure
- **Objects metadata**
  - Artwork records identified curatorially by *accession number* and technically by numeric `object id`.
  - Each object record stored as a standalone JSON file under `objects/$bucket/$id.json`.
  - **Bucket structure:** `bucket = object id / 1000` (integer division), e.g. bucket `0/` contains records with IDs 0–999.
- **Departments data**
  - Directory: `departments/`
  - Metadata for the museum’s internal departments (e.g., curatorial areas), enabling grouping or filtering of objects by department.
- **Exhibitions data**
  - Directory: `exhibitions/`
  - Metadata about exhibitions that can be used to relate objects to shows, timelines, and curatorial programs.

### Format & Access
- **JSON format**
  - All artwork metadata is provided as JSON files, suitable for direct use in scripts, applications, and analytical workflows.
- **File-by-file access**
  - Each object, department, and exhibition is accessible as an individual file via GitHub’s web interface or raw file URLs.
- **Command-line friendly**
  - Designed to work well with tools like `jq` for JSON processing.

### Example Uses (from repository documentation)
- **Collection-wide analysis**
  - Count artists represented in the collection by processing the JSON files in bulk.
  - Perform name-based queries (e.g., search for artists sharing a specific name) using shell tools like `grep` and `wc` on generated text exports.
- **Generative / experimental projects**
  - Use techniques such as Markov chains to generate synthetic artwork descriptions based on existing textual metadata.
- **Data exploration beyond the website**
  - Explore the “overall shape” of Mia’s collection data in ways not possible through the paginated collections website.

### Tooling & Repository Assets
- **Makefile**
  - Present in the repository (`Makefile`), likely providing convenience commands for building, updating, or validating data (details in repo).
- **Live update script**
  - `live-updates.fish` script suggests support for automating or streaming updates from internal sources into the public dataset.
- **.gitignore**
  - Standard Git configuration for ignoring non-essential or generated files.

### Licensing & Openness
- **License file included**
  - `LICENSE` file in the repository.
- **CC0 dedication for data**
  - Artwork metadata is explicitly published under a **CC0** (public domain) license, enabling:
    - Unrestricted reuse
    - Remixing
    - Redistribution
    - Both non-commercial and commercial applications

## Technology & Requirements

- **Primary format:** JSON
- **Recommended tools (from docs):**
  - [`jq`](https://stedolan.github.io/jq/) for JSON transformation and querying.
  - [`dadadodo`](http://www.jwz.org/dadadodo/) for Markov chain–based text generation examples.
  - Any standard, “sane” command-line environment (e.g., Unix-like shell) for running provided examples.

## Pricing

- **Free & open**
  - The repository and dataset are publicly accessible on GitHub at no cost.
  - Metadata is released under CC0, allowing free use without licensing fees.