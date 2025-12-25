# Awesome Big Data

A community-maintained, curated list of big data frameworks, tools, and educational resources, published as an open GitHub repository.

- **Website/Repo:** https://github.com/onurakpolat/awesome-bigdata
- **Category:** Themed directory (big data)
- **Tags:** big-data, data-science, distributed
- **Open Source:** Yes (see LICENSE in repository)

## Overview

Awesome Big Data aggregates links to notable big data technologies and learning materials across the ecosystem. It is inspired by other "awesome" lists (awesome-php, awesome-python, awesome-ruby) and focuses on tools and frameworks used for large-scale data storage, processing, and analysis.

## Features

- **Curated list format**
  - Manually curated collection of big data resources.
  - Community contributions accepted via GitHub.

- **Broad coverage of big data stack** (sections in the list include, but are not limited to):
  - **RDBMS** – traditional relational database systems relevant in big data contexts.
  - **Frameworks** – general-purpose big data and analytics frameworks.
  - **Distributed Programming** – libraries and platforms for distributed/parallel data processing.
  - **Distributed Filesystem** – systems for distributed storage of large data sets.
  - **Distributed Index** – technologies for indexing and searching large-scale data.
  - **Document Data Model** – document-oriented databases.
  - **Key Map Data Model** – distributed, persistent databases centered around key→map-of-values data models (often called column family stores).
  - **Key-value Data Model** – systems exposing simpler key→value interfaces.
  - **Graph Data Model** – graph databases and graph processing tools.
  - **Columnar Databases** – systems that store data column-by-column rather than row-by-row.

- **Conceptual clarifications and notes**
  - Distinguishes between:
    - Column-family-style stores (treated as **Key Map Data Model**), where each key maps to one or more maps of key–value pairs (often called column families and columns).
    - Storage-format-based **Columnar Databases**, where data is stored column-wise on disk or in memory to optimize column scans.
  - Provides references to external explanations, such as Prof. Daniel Abadi’s blog post on the two major types of column stores.

- **Educational resources**
  - Includes learning materials and references for understanding big data concepts and tools (framework documentation, blog posts, ecosystem tables like hadoopecosystemtable, etc.).

- **Ecosystem inspiration and cross-linking**
  - Inspired by multiple established "awesome" lists (awesome-php, awesome-python, awesome-ruby) and other big data overviews (e.g., hadoopecosystemtable, usefulstuff.io/big-data).

- **License information**
  - Repository includes a `LICENSE` file specifying usage and redistribution terms.

## Pricing

- Not applicable. This is a free, open GitHub list of links and resources.

## Ideal Use Cases

- Discovering big data tools and frameworks by category.
- Getting an overview of different data models (relational, key-value, document, graph, columnar, etc.).
- Using as a starting point for exploring the big data ecosystem in research, learning, or project planning.
- Contributing additional big data resources to a public, community-driven directory.