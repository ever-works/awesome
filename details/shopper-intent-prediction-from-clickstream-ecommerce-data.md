# Shopper Intent Prediction from Clickstream E‑Commerce Data

**Category:** Datasets  
**Provider:** Coveo  
**Use cases:** Shopper intent prediction, clickstream modeling, recommendation research, behavior modeling

![Pipeline](https://raw.githubusercontent.com/coveooss/shopper-intent-prediction-nature-2020/master/docs/img/pipeline.png)

---

## Overview

Public research dataset released alongside the *Nature Scientific Reports* paper “Shopper Intent Prediction from Clickstream E‑Commerce Data with Minimal Browsing Information.”

The dataset contains anonymized e‑commerce clickstream events designed for:
- Shopper intent prediction tasks
- Recommendation and behavior modeling
- Benchmarking machine learning models on minimal browsing information

Access is restricted to **research and educational** purposes and requires agreement to specific Terms and Conditions.

---

## Data Access

- Download via: https://www.coveo.com/en/ailabs/shopper-intent-prediction-from-clickstream-e-commerce-data-with-minimal-browsing-information
- Requirements:
  - Fill out a form with personal and institutional information
  - Agree to Terms and Conditions for fair usage
- Terms and Conditions:
  - Provided on the download page
  - Also included in the repository as a `.txt` file
  - Usage of the data implies acceptance of these terms

---

## Data Structure

- Format: single CSV text file, compressed in a ZIP archive
- Contents of ZIP:
  - Main dataset CSV
  - Additional copy of the Terms and Conditions
- Size:
  - **5,433,611 individual events** (clickstream records)
- Sample data:
  - A small sample CSV is included in the GitHub repository to illustrate structure and schema

### Fields

- **session_id_hash** (string)
  - Hashed identifier of the shopping session
  - A session groups together events that are at most 30 minutes apart
  - A new session ID is assigned if the same user returns after more than 30 minutes

- **event_type** (enum)
  - Event type following the Google Analytics Measurement Protocol
  - Possible values: `pageview`, `event`
  - Example: an `add` can occur on a page load or as a standalone event

- **product_action** (enum)
  - Product-level action type
  - Possible values: `detail`, `add`, `purchase`, `remove`, `click`
  - If empty, the event is a simple page view with no associated products (e.g., FAQ page)

- **product_skus_hash** (string)
  - Hashed identifiers of all products involved in the event
  - Multiple products (e.g., whole transaction) separated by `|` (pipe)
  - Present only when the event is a product-related event

- **server_timestamp_epoch_ms** (int)
  - Server timestamp in epoch milliseconds
  - Time values are shifted to enhance anonymization

- **hashed_url** (string)
  - Hashed URL of the current web page

---

## Features

- Publicly available **research-grade** e‑commerce clickstream dataset
- Based on **minimal browsing information**, suitable for studying sparse data scenarios
- Over **5.4 million** anonymized events
- Session-level grouping based on 30‑minute inactivity windows
- Standardized event semantics aligned with **Google Analytics Measurement Protocol** (`pageview` vs `event`)
- Rich product interaction labels:
  - `detail`, `add`, `purchase`, `remove`, `click`
- Supports multi-product events via `product_skus_hash` with pipe-separated SKUs
- Temporal information via millisecond epoch timestamps (time-shifted for privacy)
- URL information preserved in hashed form for structure/sequence modeling without revealing actual URLs
- Text-based CSV format enabling easy ingestion into common data and ML tools
- Includes sample file for quick schema inspection and prototyping
- Accompanied by a peer-reviewed paper offering a detailed benchmark task (shopper intent prediction)

---

## Usage & Licensing

- Intended for **research and educational** use only
- Use of the dataset **requires** acceptance of the official Terms and Conditions
- Terms are provided:
  - On the dataset download page
  - As a `.txt` file within the GitHub repository and ZIP archive

Refer to the original paper for:
- Problem formulation (shopper intent prediction task)
- Recommended splits and evaluation methodology
- Baseline approaches and benchmarks

---

## Pricing

- No explicit pricing information is provided. Dataset is described as available for **research and educational purposes**, subject to Terms and Conditions.

---

## References

- Paper: *Shopper Intent Prediction from Clickstream E‑Commerce Data with Minimal Browsing Information* (Nature Scientific Reports)
- Repository: https://github.com/coveooss/shopper-intent-prediction-nature-2020
- Dataset download and terms: https://www.coveo.com/en/ailabs/shopper-intent-prediction-from-clickstream-e-commerce-data-with-minimal-browsing-information
