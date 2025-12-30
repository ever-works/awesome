# ClueWeb09

**URL:** <http://lemurproject.org/clueweb09/>

Research corpus of about 1 billion web pages collected in 2009 by the Lemur Project, designed for information retrieval and web mining experiments. Widely used in TREC tracks and IR evaluations.

---

## Overview
- Large-scale web crawl captured in January–February 2009
- Focused on supporting research in information retrieval and human language technologies
- Includes content in 10 languages
- Common benchmark dataset for TREC and other IR experiments

---

## Features

### Dataset Size & Content
- ~1,040,809,705 web pages
- 10 languages
- ~5 TB compressed (~25 TB uncompressed)
- Organized into WARC files (~1 GB each uncompressed)
  - Each WARC file contains tens of thousands of pages (e.g., ~40,000)
  - WARC files compressed with gzip

### Web Graph
- **Entire Dataset**
  - Unique URLs: 4,780,950,903
  - Total Outlinks: 7,944,351,835
  - Size: ~325 GB uncompressed, ~105 GB compressed (URLs)
  - Size: ~71 GB uncompressed, ~24 GB compressed (outlinks)
- **TREC Category B subset (first 50M English pages)**
  - Unique URLs: 428,136,613
  - Total Outlinks: 454,075,638
  - Size: ~30 GB uncompressed, ~10 GB compressed (URLs)
  - Size: ~3 GB uncompressed, ~1 GB compressed (outlinks)
- Complete web graph available for both the entire dataset and Category B subset
- Crawl progression statistics available online

### Distribution Options
- **Full Dataset (Category A)**
  - Distributed as tarred/gzipped files
  - Delivered on a single 8 TB hard disk (HDD)
- **TREC Category B Subset**
  - First 50 million English pages
  - Tarred/gzipped files on one 500 GB HDD
- **Japanese Subset (JA)**
  - Japanese-language portion of the crawl
  - Tarred/gzipped files on one 500 GB HDD
- **T11Crowd Subset**
  - Subset used by the TREC 2011 Crowdsourcing track
  - Downloadable from the web

### Media & Hardware Details
- Distributed on standard 3.5" SATA 6 Gbit/s HDDs
- Compatible with most SATA interfaces, including external USB–SATA enclosures
- Disk filesystems:
  - Disks shipped after June 21, 2023: Linux ext4
  - Older disks: Linux ext3
- Note on large disks (≥1 TB):
  - Users must ensure OS and hardware support large-capacity drives
  - Some SATA enclosures may not support large disks

### File Formats & Sample Data
- Primary format: WARC (Web ARChive) files
- Each WARC file:
  - ~1 GB uncompressed
  - Contains tens of thousands of web pages
  - Compressed with gzip
- Detailed format documentation and sample files available on the Dataset Information and Sample Files pages

### Online Services
- **Batch Query Service for ClueWeb09**
  - Search ClueWeb09 using the Indri search engine
  - Supports:
    - Category A English
    - Category B dataset

### Related Resources & Documentation
- Dataset details, record counts, and language distribution
- Dataset Information & Sample Files page (format specs and examples)
- Crawl statistics page describing how the crawl progressed
- Additional pages for:
  - How to obtain the dataset
  - Related data sets
  - Indexing with Indri
  - Wiki, mailing lists / email
  - FAQ

---

## Category
- Themed Directories / Datasets

## Tags
- datasets
- web
- information-retrieval

---

## Pricing

The provided content does not specify pricing or licensing terms. Users should consult the ClueWeb09 "How to Get It" or FAQ pages for current access conditions and any associated fees.