# Cooper-Hewitt Collection Database

## Overview
The Cooper-Hewitt Collection Database is an open dataset from the Cooper Hewitt, Smithsonian Design Museum, providing public access to a large portion of the museum’s documented collection. It is distributed via a GitHub repository and is also accessible through a web collection interface.

- **Type:** Open dataset
- **Category:** Datasets
- **Source:** Cooper Hewitt, Smithsonian Design Museum
- **Access:** Free public download
- **Repository:** https://github.com/cooperhewitt/collection

## Features
- **Extensive collection coverage**
  - Approximately 75% of the museum’s documented collection data made public.
  - Mirrors data from the online collection interface: http://collection.cooperhewitt.org

- **Structured dataset organization (repository folders)**
  - `objects/` – Object-level metadata for items in the collection.
  - `people/` – Data about people associated with the collection (e.g., designers, makers, etc.).
  - `departments/` – Information about museum departments.
  - `exhibitions/` – Data related to exhibitions.
  - `periods/` – Time-period related information (e.g., historical or stylistic periods).
  - `roles/` – Role definitions for entities in the dataset (e.g., artist, manufacturer).
  - `types/` – Classification types or categories used within the collection.
  - `meta/` – Miscellaneous or higher-level metadata and configuration for the dataset.

- **Programmatic access & tooling**
  - `bin/` directory with scripts and tools for working with the dataset (e.g., build, transform, or export tasks).
  - `Makefile` for automating dataset-related operations (build, update, or processing steps) via standard command-line workflows.

- **Documentation & metadata files**
  - `README.md` – Main project and dataset documentation (usage, structure, and context).
  - `README.CONCORDANCES.md` – Details on concordances/mappings to external identifiers or systems.
  - `LICENSING.md` – License information and terms of use for the dataset.
  - `PUBDATE.md` – Publication date or release metadata for the dataset.
  - `.gitattributes` and `.gitignore` – Repository configuration for consistent handling of files.

- **Open access orientation**
  - Data is explicitly made available for public access and free download.
  - Designed so users can view and analyze “everything at once” to discover new connections and insights in the collection.

## APIs & Integrations
- The dataset is designed to complement the museum’s web collection interface and related programmatic access.
- Usable as a standalone dataset or in combination with tools and scripts from the repository.

## Use Cases
- Cultural heritage and museum informatics research.
- Data visualization and digital humanities projects.
- Education and teaching resources on design history.
- Building custom interfaces, search tools, or analysis pipelines for museum collection data.

## Pricing
- **Free** – The dataset is made available for free public download; no pricing tiers are indicated in the repository content.

## Tags
- datasets
- museums
- apis
