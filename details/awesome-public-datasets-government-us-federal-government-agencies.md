# Awesome Public Datasets – Government: U.S. Federal Government Agencies

An Awesome catalog entry referencing Data.gov’s official **Metrics** section, summarizing open data usage across U.S. federal government agencies.

- **Name:** Awesome Public Datasets – Government: U.S. Federal Government Agencies  
- **Source:** [Data.gov Metrics](http://www.data.gov/metrics)  
- **Category:** Themed directories  
- **Tags:** government, datasets, open-data  
- **Brand:** us-federal-government

---

## Overview

This entry points to Data.gov’s monthly **metrics dashboard** for U.S. federal open data. The metrics describe how the Data.gov catalog is used: overall traffic, device breakdowns, and which datasets and external links are most frequently accessed.

The metrics page is an **official U.S. government (.gov) site** served over HTTPS, indicating it is an authoritative source on U.S. federal open data usage.

---

## Features

### 1. Monthly Sitewide Metrics
- Metrics are reported for a **specific calendar month**, ending at the stated **Report Date** (e.g., 2025‑11‑30).
- Data is **refreshed at the beginning of each new month** to show the previous calendar month.
- Includes an overall **Total Pageviews** value (e.g., `3,900,633` for the sample month).

### 2. Users by Device Type
- Breaks down Data.gov usage by **device category**:
  - Desktop
  - Mobile
  - Tablet
  - Smart TV
- Shows for each device category:
  - Number of users
  - Percentage of total users
- Example for the reference month:
  - Desktop: 2,941,955 users (98.35%)
  - Mobile: 47,467 users (1.59%)
  - Tablet: 2,011 users (0.07%)
  - Smart TV: 16 users (0.00%)
- Provides a **downloadable CSV report** for full device data:
  - `global__device_category__last30.YYYY-MM-DD.csv`

### 3. Most Downloaded Dataset Files
- Lists the **Top 10 most downloaded dataset files** for the month.
- For each file, the table includes:
  - File URL (direct download endpoint, usually CSV or similar)
  - Page title in the Data.gov catalog
  - Download count for the period
- Example entries include datasets on:
  - Electric Vehicle Population Data
  - Crime Data from 2020 to Present
  - Supply Chain Greenhouse Gas Emission Factors (NAICS-6)
  - Lottery Powerball Winning Numbers
  - U.S. Chronic Disease Indicators
  - Warehouse and Retail Sales
  - Drug overdose death rates by drug type and demographics
  - Motor Vehicle Collisions – Crashes
- Provides a **downloadable CSV** for the complete most-downloaded list:
  - `global__download_requests__last30.YYYY-MM-DD.csv`

### 4. Most Clicked Outbound Links
- Tracks the **Top 10 outbound link clicks** from Data.gov to external domains.
- For each outbound link, the table includes:
  - Link URL (external site)
  - Page title from which the link was clicked
  - Click count
- Provides a **downloadable CSV** for full outbound link metrics:
  - `global__link_requests__last30.YYYY-MM-DD.csv`

### 5. Organizational Metrics Context (Implied)
- Section header **“Metrics by Organization”** indicates data can be broken down by **federal organizations or agencies**, though detailed org-level rows are not shown in the provided excerpt.
- Intended to help understand open data publication and access **across U.S. federal government agencies**.

### 6. Security and Authenticity Indicators
- Identifies the site as an **official U.S. government website** (`.gov` domain).
- Explains that:
  - `.gov` or `.mil` endings indicate federal sites.
  - `https://` ensures an encrypted and secure connection.
- Aimed at assuring users they are viewing **authoritative government metrics**.

---

## Data Format & Access

- Metrics are primarily presented as **HTML tables** on the metrics page.
- Full underlying datasets are provided as **CSV files** for:
  - Users by Device Type
  - Most Downloaded Dataset Files
  - Most Clicked Outbound Links
- Files are hosted on an **official government S3-compatible storage** (`s3-us-gov-west-1.amazonaws.com`).

---

## Use Cases

- **Researchers and analysts**: Track trends in public interest and usage of specific federal datasets.
- **Government agencies**: Monitor engagement with their published open data assets.
- **Open data advocates / journalists**: Identify highly used datasets and topics of public interest.
- **Developers and data product teams**: Understand the demand for certain file formats and subject areas.

---

## Pricing

- Access to the Data.gov metrics and associated CSV reports is **free** as part of the U.S. federal government’s open data initiative. No paid plans or pricing tiers are specified.