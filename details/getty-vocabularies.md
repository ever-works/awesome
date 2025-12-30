# Getty Vocabularies

Authoritative controlled vocabularies for art, architecture, geography, artists, and related cultural heritage data, published as Linked Open Data and accessible via web services and downloadable datasets.

---

## Overview
- **Vocabularies**: AAT, TGN, ULAN, CONA
- **Domain**: Art, architecture, material culture, archival and bibliographic materials, visual surrogates
- **Purpose**: Provide structured, standards-compliant terminology and identifiers for cataloging, research, and improving access to databases and websites
- **Publisher**: Getty Vocabulary Program (GVP), The J. Paul Getty Trust
- **Growth model**: Expanded and refined through community and institutional contributions

---

## Features

### Core Vocabularies
- **Art & Architecture Thesaurus (AAT)**
  - Structured vocabulary of generic concepts related to art and architecture
  - Includes terms, descriptions, and related information
  - Supports disambiguation of similar concepts (e.g., “catherine wheel” vs “rose window”)

- **Getty Thesaurus of Geographic Names (TGN)**
  - Structured vocabulary of geographic names and places important to art and architecture
  - Includes names, descriptions, and other place-related information
  - Captures historical and variant place names (e.g., “London” vs “Londinium”)

- **Union List of Artist Names (ULAN)**
  - Structured vocabulary of artists and architects
  - Includes names, biographical data, and related information
  - Handles variant names and identity disambiguation (e.g., “Titian” vs “Tiziano Vecellio”)

- **CONA (Cultural Objects Name Authority)**
  - Mentioned as part of the Getty vocabularies
  - Covers cultural objects and related materials (implied by description)

### Standards and Data Model
- Compliant with international standards for controlled vocabularies and cultural heritage metadata
- Published as Linked Open Data (LOD)
- **Ontology versions & updates**
  - Documented ontology and mapping changes for Version 2.0 and Version 3.0
  - Dedicated change documentation pages for ontology evolution

### Semantic Representations
- **Linked.Art Semantic Representation**
  - Dedicated website and model documentation
  - Default model for JSON / JSON-LD serializations
  - Semantic resolution support
  - Activity Stream endpoint: `https://data.getty.edu/vocab/activity-stream`
  - SPARQL Endpoint: `https://data.getty.edu/vocab/sparql`
  - SPARQL UI: `https://data.getty.edu/vocab/sparql-ui`

- **GVP Semantic Representation**
  - HTML documentation (for linking) and PDF (for printing)
  - Details of GVP URLs and prefixes
  - Semantic resolution examples and URI usage
  - List of all prefixes in `prefixes.ttl`
  - Comprehensive sample SPARQL queries

- **GVP Ontology**
  - Available in multiple serializations:
    - HTML view
    - RDF/XML
    - Turtle (TTL)

### Datasets and Downloads
- Datasets provided as N-Triples ZIP files (with guidance in Export Files documentation):
  - **AAT**
    - `full.zip` – all statements
    - `explicit.zip` – only explicit statements
  - **TGN**
    - `full.zip` – all statements
    - `explicit.zip` – only explicit statements
  - **ULAN**
    - `full.zip` – all statements
    - `explicit.zip` – only explicit statements
- **VOID description**
  - `void.ttl` file describing datasets (per VoID vocabulary)
- **Associative Relationship Types**
  - Full matrix of relationship codes
  - Provided as PDF and Excel files
- General background on Getty Linked Open Data projects

### Access & Exploration Tools
- **Text search interface**
  - Vocabulary selection: All / AAT / TGN / ULAN
  - Search by:
    - Free text
    - Concept ID
  - Query behavior:
    - Multiple words combined with logical AND
  - Search modes:
    - **Brief** – search only terms
    - **Full** – search scope notes and terms

- **SPARQL query interface**
  - Access via SPARQL link in the header
  - In-page sample queries below the query box
  - Extended sample queries documented in the “Sample Queries” section

---

## Technical Details
- Data published as RDF with N-Triples exports
- Ontology and vocabularies accessible via HTTP URIs with semantic resolution
- SPARQL endpoint and UI for programmatic and interactive querying
- Activity Streams for update/changes feed
- Use of standard vocabularies and prefixes (documented in `prefixes.ttl`)

---

## Use Cases
- Cataloging art, architecture, and cultural heritage collections
- Normalizing artist names, geographic names, and conceptual terms in collection management systems
- Enhancing search and discovery in museum and library databases
- Powering Linked Data and semantic web applications in the cultural heritage sector

---

## Pricing
- No pricing information is provided in the available content. The vocabularies and datasets are presented as Linked Open Data with public endpoints and downloadable files; licensing or usage terms, if any, are not specified here.