# Delve Datasets for Classification and Regression

A collection of standardized datasets for developing, evaluating, and comparing machine learning methods, maintained by the University of Toronto’s DELVE project.

## Overview

- **Type:** Dataset collection
- **Domain:** Machine learning (classification and regression)
- **Maintained by:** University of Toronto, DELVE project
- **Primary use:** Benchmarking, assessment, and development of learning algorithms
- **Access:** Downloadable as gzipped-tar files
- **Recommended tooling:** Delve software environment (for maximum benefit)

## Features

### Dataset Organization
- Datasets grouped into **categories by recommended use**:
  - **Assessment datasets** – for reporting final results; methods should be run once per task without tuning on test data.
  - **Development datasets** – (mentioned conceptually; used for method development and tuning, details not in excerpt).
  - **Historical datasets** – (mentioned conceptually as a category; details not in excerpt).
- Within each category, datasets are further labeled as:
  - **Regression** – continuous target/prototask.
  - **Classification** – discrete target/prototask.

### Access & Format
- Each dataset (or **family of datasets**) has:
  - A **brief overview page**.
  - Often **detailed documentation** (per-dataset docs pages).
- Datasets available as **gzipped-tar archives** via FTP.
- **Installation instructions** for downloaded datasets are provided on the site (installation section referenced but not expanded in the excerpt).
- A **summary table** of all datasets is available for quick reference.

### Tooling Integration
- Designed to work with the **Delve software environment**, which provides:
  - Structured access to datasets.
  - Additional utilities for evaluation (details in a separate "utils" section, not included here).

### Dataset Types and Examples

#### Assessment Regression Datasets

Intended for reporting performance; do not tune on test data.

1. **abalone**
   - **Task:** Predict the age of abalone from physical measurements.
   - **Source:** UCI Machine Learning Repository.
   - **Download:** `abalone.tar.gz` (gzipped-tar archive via FTP).

2. **bank (bank-family)**
   - **Type:** Family of synthetically generated datasets.
   - **Task domain:** Simulation of how bank customers choose their banks.
   - **Prototask:** Predict the fraction of bank customers who leave the bank because of full queues.
   - **Download:** `bank-family` (tar archive via FTP).

3. **census-house**
   - **Task:** Predict median house prices from 1990 US census data.
   - **Download:** `census-house.tar.gz` (gzipped-tar archive via FTP).

4. **comp-activ**
   - **Task:** Predict computer system activity from system performance measures.
   - **Download:** `comp-activ.tar.gz` (gzipped-tar archive via FTP).

5. **pumadyn family of datasets**
   - **Type:** Family of synthetically generated datasets.
   - **Task domain:** Dynamics of a Unimation Puma 560 robot arm.
   - **Description:** Generated from a realistic simulation of the robot arm’s dynamics.
   - **Download:** `pumadyn-family` (tar archive via FTP).

#### Assessment Classification Datasets

1. **adult**
   - **Task:** Predict whether an individual's annual income exceeds $50,000 based on census data.
   - **Source:** UCI Machine Learning Repository.
   - **Download:** `adult.tar.gz` (gzipped-tar archive via FTP).

2. **splice**
   - **Task:** Classification on splice junction data (full description truncated in provided content, but dataset is listed as an assessment classification dataset).
   - **Download:** `splice.tar.gz` (gzipped-tar archive via FTP; link partially shown in excerpt).

### Documentation & Notes
- An **important note for users with version 1.0 of the Delve software** is provided on a separate page.
- Each dataset/family has its own **`desc.html`** page with additional details (schema, tasks, etc.).

## Category
- **Directory category:** datasets
- **Tags:** datasets, machine-learning, benchmark

## Pricing
- No pricing information is mentioned in the provided content; datasets appear to be freely downloadable from the University of Toronto’s DELVE project site.
