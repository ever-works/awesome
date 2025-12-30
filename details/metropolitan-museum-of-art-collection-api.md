# Metropolitan Museum of Art Collection API

## Overview
The Metropolitan Museum of Art Collection API is a public, RESTful JSON web service providing open access to metadata and images for artworks in The Met’s collection. It exposes select datasets covering more than 470,000 artworks, including high‑resolution JPEG images for works in the public domain. The data is released under the Creative Commons Zero (CC0) license, allowing unrestricted commercial and noncommercial use.

## Key Details
- **Type:** Public collection / museum dataset API
- **Provider:** The Metropolitan Museum of Art (The Met)
- **Data Coverage:** 470,000+ artworks from The Met’s collection
- **Format:** RESTful API, JSON responses; images in JPEG
- **License:** Creative Commons Zero (CC0 1.0)
- **Authentication:** No API key or registration required (as of latest info)
- **Rate Limit Guidance:** Up to ~80 requests per second
- **Primary Use Cases:** Research, applications, visualizations, educational projects, cultural heritage tools, and other art/dataset-driven projects

## Features

### Open Access Datasets
- Provides **select datasets** for hundreds of thousands of artworks in The Met collection.
- Includes **artwork metadata** and **identifying data** even for artworks under copyright.
- All open access data is provided under **CC0**, enabling:
  - Unrestricted commercial use
  - Unrestricted noncommercial use
  - Reuse in any media without permission or fee

### High-Resolution Images
- Access to **high resolution images (JPEG)** for artworks in the **public domain**.
- Images are linked to the corresponding object metadata via the API.

### RESTful JSON API
- Exposes The Met’s open access data via a **RESTful web service**.
- Responses are returned in **JSON** format.

### Objects Endpoint
- **Endpoint:** `GET /public/collection/v1/objects`
- **Purpose:** Retrieve a listing of all valid object IDs available in the collection.
- **Parameters:**
  - `metadataDate` (datetime, e.g. `YYYY-MM-DD`)
    - Returns any objects with data updated after the specified date.
  - `departmentIds` (integers corresponding to department IDs, delimited with `|`, e.g. `1` or `3|9|12`)
    - Returns any objects belonging to one or more specified departments.
- **Response fields:**
  - `total` (int)
    - Total number of publicly available objects matching the request.
  - `objectIDs` (array of int)
    - Array of object IDs for publicly available objects.

#### Example: All Objects
- **Request:**
  - `https://collectionapi.metmuseum.org/public/collection/v1/objects`
- **Response (structure):**
  - `{
      "total": <int>,
      "objectIDs": [1, 2, 3, ...]
    }`

#### Example: Filtered by Department
- **Request (single department):**
  - `https://collectionapi.metmuseum.org/public/collection/v1/objects?departmentIds=1`
- **Request (multiple departments):**
  - `https://collectionapi.metmuseum.org/public/collection/v1/objects?departmentIds=3|9|12`
- **Response (structure):**
  - `{
      "total": <int>,
      "objectIDs": [1, 2, 3, ...]
    }`

### Search Endpoint
- A dedicated **search endpoint** exists (not fully described in the provided content).
- Additional search filters were introduced in the November 17, 2020 update.

### Metadata Enhancements
- Additional metadata fields were made available in the API as of November 4, 2020 (specific fields not listed in the provided content).

### Access & Usage
- **Open access**: No registration or API key required.
- **Usage terms**: Subject to The Met’s terms and conditions.
- **Intended uses**: To support search, reuse, analysis, and interaction with the museum’s collection across various media and applications.

## Pricing
- **Cost:** Free
- **Usage:** No fees for accessing data or images covered by the Open Access program (subject to terms and conditions and the CC0 license for open access content).

## Links
- **API & Documentation:** https://metmuseum.github.io/
- **Open Access GitHub page:** https://github.com/metmuseum/openaccess
- **Terms and Conditions:** https://www.metmuseum.org/information/terms-and-conditions
