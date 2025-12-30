# LAW Network Datasets

**URL:** <http://law.di.unimi.it/datasets.php>

## Overview
The LAW Network Datasets, maintained by the Laboratory for Web Algorithmics (LAW) at the University of Milan, provide large-scale web and hyperlink graph datasets. These datasets are suitable for experiments in web mining, graph algorithms, and network analysis, and are distributed in highly compressed formats.

## Features
- **Large-Scale Graph Collections**
  - Web and network graphs organized into homogeneous groups.
  - Each group includes multiple graph instances.

- **Highly Compressed Graph Format**
  - Graphs compressed using:
    - LLP (Layered Label Propagation).
    - WebGraph framework.
  - For each graph/group, metadata typically includes:
    - Crawl date.
    - Number of nodes.
    - Number of arcs.
    - Bits per link for the highly compressed version.
    - Compression ratio relative to the information-theoretical lower bound.

- **Multiple Compression/Access Trade-offs**
  - A highly compressed version (optimized for space and reporting compression ratios).
  - A general-usage version with faster random access but worse compression ratio.

- **Software Ecosystem Integration**
  - **Java WebGraph**: Datasets can be downloaded and used via the Java WebGraph library.
  - **Rust WebGraph**: Usage supported via the Rust implementation of WebGraph (crate `webgraph`).
  - **JGraphT Integration**:
    - Graphs can be loaded and analyzed in JGraphT using WebGraph adapters.
    - For graphs with fewer than 2³¹ arcs, a serialized succinct JGraphT representation is provided.

- **Documentation & Tutorial**
  - A dedicated tutorial explains how to download and use the datasets with WebGraph (Java and Rust versions).

- **Data Provenance and Tools Acknowledgment**
  - Clear guidance on how to acknowledge:
    - WebGraph compression framework.
    - LLP ordering method.
    - Rust version of WebGraph.
    - UbiCrawler (for datasets gathered with this crawler).
    - BUbiNG (for datasets gathered with this crawler).

## Integrations
- Java WebGraph
- Rust WebGraph (`webgraph` crate)
- JGraphT (via WebGraph adapters and succinct serialized representations)

## Usage & Citation Requirements
When publishing results based on these graphs, users are expected to:
- Cite the WebGraph framework and LLP compression papers.
- Cite the Rust WebGraph paper if the Rust implementation is used.
- Cite UbiCrawler and/or BUbiNG papers when using datasets gathered with those crawlers.

## Category
- Themed directories / data resource directory

## Tags
- web
- graph
- datasets

## Pricing
- Not specified on the provided content (datasets are typically research resources; no pricing information is given).
