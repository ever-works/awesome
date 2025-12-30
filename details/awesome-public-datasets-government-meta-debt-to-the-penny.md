# Awesome Public Datasets – Government (Meta: Debt to the Penny)

**Category:** Themed Directories  
**Tags:** datasets, finance, government  
**Source:** [U.S. Treasury – Debt to the Penny](https://fiscaldata.treasury.gov/datasets/debt-to-the-penny/debt-to-the-penny)

Awesome Public Datasets entry for the official U.S. Treasury **Debt to the Penny** dataset portal, which provides daily figures on total public debt outstanding.

---

## Overview

The **Debt to the Penny** dataset publishes official, daily data on the **total outstanding public debt of the United States**. It breaks down the national debt into:

- **Debt Held by the Public** (marketable and non‑marketable securities held outside the federal government)
- **Intragovernmental Holdings** (obligations the federal government owes to its own trust funds and certain government accounts)
- **Total Public Debt Outstanding (TPDO)** (sum of the two components)

Coverage begins **1993‑04‑01** and extends through **2025‑12‑26**, with data **released daily**. The dataset is **updated at the end of each business day** using values from the previous business day.

---

## Features

### Data content

- **Total Public Debt Outstanding (TPDO)**
  - Sum of intragovernmental holdings and debt held by the public.
  - Provides the official “national debt” figure for each record date.

- **Debt Held by the Public** (`debt_held_public_amt`)
  - All federal debt held by:
    - Individuals
    - Corporations
    - State and local governments
    - Federal Reserve Banks
    - Foreign governments
    - Other entities outside the U.S. federal government
  - Excludes Federal Financing Bank (FFB) securities.
  - Composed of:
    - Treasury Bills
    - Treasury Notes
    - Treasury Bonds
    - Treasury Inflation‑Protected Securities (TIPS)
    - Floating Rate Notes (FRNs)
    - Domestic Series securities
    - Foreign Series securities
    - State and Local Government Series (SLGS)
    - U.S. Savings Securities
    - A portion of Government Account Series (GAS) securities

- **Intragovernmental Holdings** (`intragov_hold_amt`)
  - Government Account Series (GAS) securities held by:
    - Government trust funds
    - Revolving funds
    - Special funds
  - Includes Federal Financing Bank (FFB) securities.

- **Record Date** (`record_date`)
  - Date on which the data was published.
  - Stored as a `DATE` field.

- **Source Line Number** (`src_line_nbr`)
  - Indicates the row of the corresponding source table where the data point can be found.
  - Useful for:
    - Reconstructing the published report’s structure
    - Understanding hierarchies within the source table

### Temporal coverage & update frequency

- **Date range:** 1993‑04‑01 to 2025‑12‑26
- **Update frequency:** Daily
- **Update timing:** End of each business day (for the previous business day)

### Data structure

- **Single primary data table:** `Debt to the Penny`
- **Field-level metadata:**
  - Data type (e.g., `DATE`, `CURRENCY`, `INTEGER`)
  - Required/optional indicator

### Access & formats

- **Web data portal** with search and dataset view
- **API access** via an “API Quick Guide” (on the source site) for programmatic retrieval
- **Reports and files** section (file list provided on source site when available)

### Notes & Known Limitations

- **Definition of Total Public Debt Outstanding (TPDO):**
  - TPDO = Debt Held by the Public + Intragovernmental Holdings.
  - In this dataset, **Intragovernmental Holdings includes FFB securities**.

- **Relationship to other Fiscal Data national debt datasets:**
  - **Debt to the Penny**
    - Contains TPDO plus a breakout of Debt Held by the Public and Intragovernmental Holdings.
    - Intragovernmental Holdings includes FFB securities.
  - **Historical Debt Outstanding**
    - Contains TPDO only, **no breakout** of Debt Held by the Public vs Intragovernmental Holdings.
    - TPDO includes FFB securities.
  - **Daily Treasury Statement (DTS)**
    - Contains Debt Held by the Public and Intragovernmental Holdings, but **does not aggregate** them into TPDO.
    - Intragovernmental Holdings includes FFB securities.

These definitional nuances matter when comparing national debt figures across Treasury datasets.

---

## Use Cases

- Time‑series analysis of U.S. national debt from 1993 onward.
- Research on the composition of federal debt between public and intragovernmental holders.
- Consistency checks or reconciliations against other Treasury debt series (e.g., DTS, Historical Debt Outstanding).

---

## Pricing

- **Access cost:** Public, official U.S. government dataset; available **free of charge** for use and analysis.