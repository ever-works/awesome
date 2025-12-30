# Merklemap DNS Records Dataset

**Category:** Datasets  
**Provider:** Merklemap  
**Slug:** `merklemap-dns-records-dataset`  
**Source:** https://www.merklemap.com/dns-records-database

![Merklemap](https://www.merklemap.com/assets/logo.png)

## Overview

The Merklemap DNS Records Dataset is a large-scale DNS (Domain Name System) records database containing more than 4 billion records across hundreds of millions of domains. It is intended for Internet measurement, cybersecurity, DNS research, and data enrichment, and is provided in a JSON/JSONL format suitable for large-scale analysis.

## Features

- **Scale & Coverage**
  - Over 4 billion DNS records.
  - Coverage across a very large number of domains (hundreds of millions).
  - Provides a broad, global view of DNS infrastructure and activity.

- **Record Types**
  - Includes common DNS record types:
    - A
    - AAAA
    - CNAME
    - MX
    - NS
    - TXT
  - May include additional DNS record types beyond those listed.

- **Data Format**
  - Delivered as `dns_records.jsonl` (JSON Lines format).
  - Each line contains a JSON object with at least:
    - `hostname`: the queried domain/hostname, e.g. `"example.com"`.
    - `results`: array of query result objects, including:
      - `success.query`: DNS query string (e.g. `"example.com IN A"`).
      - `success.query_timestamp`: timestamp of the DNS query (RFC3339 / ISO-like format).
      - `success.records`: object mapping record type to values, e.g.:
        - `A: ["192.0.2.1", "192.0.2.2"]`
  - Optimized for integration with analysis pipelines and tooling.

- **File Size & Distribution**
  - Compressed size: **41 GiB**.
  - Uncompressed size: **417.6 GiB**.

- **Intended Use Cases**
  - **Cybersecurity Research**
    - Identify potentially malicious domains and suspicious IP addresses.
    - Study DNS-based attack infrastructure and threat campaigns.
  - **Threat Hunting**
    - Search for indicators of compromise (IOCs) across large DNS datasets.
    - Surface hidden or emerging threats through DNS patterns.
  - **Network Troubleshooting**
    - Investigate DNS-related issues.
    - Analyze misconfigurations or resolution failures.
  - **Domain & Infrastructure Intelligence**
    - Examine domain ownership and hosting infrastructure.
    - Map relationships among domains, IPs, and name servers.
    - Support competitive analysis and market research.
  - **Brand Protection**
    - Monitor DNS records for phishing, typosquatting, or brand misuse.
  - **Data Enrichment**
    - Augment existing security, network, or business datasets with DNS context.

## Licensing

- Licensed under **CC BY-NC-SA 4.0** (Creative Commons Attribution–NonCommercial–ShareAlike 4.0).
- License details: https://creativecommons.org/licenses/by-nc-sa/4.0/

## Pricing

- The dataset is offered under a **non-commercial (CC BY-NC-SA 4.0) license** as described above.
- For **commercial use**, access is gated through a request form:  
  https://docs.google.com/forms/d/e/1FAIpQLSe4uzrm0hBJZwD_64WRjyWLs2jfhCvOHH4CknzIMPRggfBgEg/viewform  
- No specific commercial pricing tiers or plan details are provided in the available content.