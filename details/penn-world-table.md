# Penn World Table (PWT 11.0)

![Penn World Table](https://www.rug.nl/research/ggdc/img/pwt-homepage.png)

**Website:** https://www.rug.nl/ggdc/productivity/pwt/?lang=en  
**Provider:** Groningen Growth and Development Centre, University of Groningen  
**Category:** Datasets  
**Tags:** datasets, macroeconomics, economics

---

## Overview

Penn World Table (PWT) 11.0 is an internationally comparable database of national accounts, providing measures of income, output, inputs, and productivity for 185 countries from 1950 to 2023. It is widely used for macroeconomic and productivity research, especially for cross-country comparisons and growth analysis.

PWT 11.0 is a major update to PWT 10.01; details of changes are documented in the “What is new in PWT 11.0” document.

---

## Key Details

- **Version:** 11.0  
- **Coverage:** 185 countries, 1950–2023  
- **Focus:** Relative levels and time-series of income, output, input use, productivity, and price levels  
- **Primary use cases:** Cross-country growth regressions, productivity analysis, comparisons of living standards and productive capacity

---

## Data Access

- **Full dataset (Dataverse):** https://doi.org/10.34894/FABVLR  
- **Download formats:**
  - Excel: https://dataverse.nl/api/access/datafile/554105
  - Stata: https://dataverse.nl/api/access/datafile/554030
- **Online data access / query tool:** https://pwt-data-tool.streamlit.app

---

## Documentation & User Resources

- **User Guide:** User Guide to PWT 11.0 (detailed documentation and variable guide)
  - https://dataverse.nl/api/access/datafile/554025
- **What is new in PWT 11.0:** Overview of methodological and data changes relative to PWT 10.01
  - https://dataverse.nl/api/access/datafile/554031
- **Background/interpretation resources:**
  - VoxEU column: “Recasting international income differences: The next generation of Penn World Table”
  - Productivity Institute blog on Penn World Table
- **Previous version:** PWT 10.01 (archived release information available on the GGDC site)

---

## Features

### Coverage & Content

- Time series for **185 countries** from **1950–2023**
- Measures of:
  - **Real GDP** (multiple concepts and methods)
  - **Output and inputs** (e.g., capital and labour, though specific breakdowns are detailed in the full documentation)
  - **Productivity** measures
  - **Price levels and purchasing power parities (PPPs)**
- Consistent, internationally comparable data, suitable for cross-country and over-time analysis.

### Selected Core Variables (examples)

The online tool provides “selective data access” for specific variables. Examples include:

- **RGDPNA**  
  - *Description:* Real GDP using national-accounts growth rates.  
  - *Use:* Comparing output-based growth rates across countries (e.g., dependent variable in cross-country growth regressions).

- **CGDPe**  
  - *Description:* Expenditure-side real GDP at current PPPs.  
  - *Use:* Comparing relative living standards across countries at a single point in time (e.g., initial level in growth regressions requiring relative living standards).

- **CGDPo**  
  - *Description:* Output-side real GDP at current PPPs.  
  - *Use:* Comparing relative productive capacity across countries at a single point in time (e.g., initial level in growth regressions requiring productive capacity or productivity).

- **RGDPe**  
  - *Description:* Expenditure-side real GDP at chained PPPs.  
  - *Use:* Comparing relative living standards over time and across countries with a time-consistent PPP basis.

(Additional variables and detailed definitions are listed in the User Guide and the online data tool.)

### Access & Integration

- Bulk download via Dataverse (with a persistent DOI for citation and reproducibility).
- Ready-to-use **Excel** and **Stata** files.
- Web-based querying through the **online data access tool** for selective extraction and quick exploration.

### Versioning & Updates

- Clearly versioned releases (e.g., PWT 10.01, PWT 11.0) with:
  - Dedicated “What is new” documentation per release.
  - Archived access to prior versions for reproducible research.
- Communication about new releases via the project’s Twitter account: **@PennWorldTable**.

### Attribution & Licensing

- **Attribution requirement:** When using the data, users should cite:
  - Feenstra, Robert C., Robert Inklaar and Marcel P. Timmer (2015), “The Next Generation of the Penn World Table,” *American Economic Review*, 105(10), 3150–3182, available at https://www.ggdc.net/pwt
- **License:**
  - Penn World Table 11.0 is licensed under the **Creative Commons Attribution 4.0 International (CC BY 4.0)** license.
- **Funding acknowledgement:** Supported by the **STEG project**, funded by the UK Foreign, Commonwealth and Development Office.

---

## Pricing

- No pricing information is indicated in the provided content.  
- Under the CC BY 4.0 license, the dataset is available for use with proper attribution.

---

## Ideal Use Cases

- Cross-country growth and convergence studies.
- Analysis of international differences in living standards and productive capacity.
- Productivity and structural change research.
- Policy analysis requiring harmonized macroeconomic indicators over long time horizons.