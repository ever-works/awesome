# B3FD – Biometrically Filtered Famous Figure Dataset for Age Estimation

**Category:** Datasets  
**Tags:** datasets, machine learning, computer vision  
**Source:** https://github.com/kbesenic/B3FD

## Overview
B3FD (Biometrically Filtered Famous Figure Dataset) is a publicly available, unconstrained facial image dataset for age estimation. It is derived from the IMDB-WIKI and CACD datasets and automatically cleaned using unsupervised biometric filtering methods to remove faulty web-scraped samples.

- Total images: **375,592** facial samples
- Unique subjects: **53,759** (≈ **6.99** images per subject)
- Age range: **0–100 years**
- Primary use: **Facial age (and partially gender) estimation**
- Intended use: **Academic research**

## Features

- **Biometric filtering and cleaning**
  - Derived from **IMDB-WIKI** and **CACD** facial datasets.
  - Unsupervised biometric filtering used to remove erroneous or noisy web-scraped samples.
  - Removal rates:
    - IMDB-WIKI: **53%** of samples removed.
    - CACD: **20%** of samples removed.

- **Dataset composition**
  - Total images: **375,592**.
  - Total unique subjects: **53,759**.
  - Average samples per subject: **6.99**.
  - Age labels from **0 to 100**.

- **Subsets**
  - **B3FD-IWS (IMDB-WIKI subset)**
    - 245,204 processed samples.
    - 53,568 unique subjects.
    - ≈ 4.58 samples per subject.
  - **B3FD-CS (CACD subset)**
    - 130,388 processed samples.
    - 1,831 unique subjects.
    - ≈ 71.21 samples per subject.
  - Subsets intended for scenarios with data-origin constraints (e.g., only IMDB-WIKI- or CACD-derived data).

- **Image properties**
  - All images are **pre-aligned**.
  - **Cropped with 50% context** around the face.
  - **Resized to 256×256 pixels**.

- **Metadata**
  - Main metadata file: `B3FD_metadata/B3FD_age.csv`
    - Contains pairs of **image paths** and **age labels** for the full dataset.
  - Subset metadata files:
    - `B3FD_metadata/B3FD-IWS_age.csv` (IMDB-WIKI-derived subset) – image path + age.
    - `B3FD_metadata/B3FD-CS_age.csv` (CACD-derived subset) – image path + age.
  - Additional age + gender metadata (IMDB-WIKI-origin samples):
    - `B3FD_metadata/B3FD-IMDB_age_gender.csv`
    - `B3FD_metadata/B3FD-WIKI_age_gender.csv`

- **Filtration lists**
  - Provided under `B3FD_filtration_lists` archive.
  - Can be used if you wish to re-apply or adjust image processing with your own pipeline while preserving the same filtered sample selection.

- **Performance context**
  - According to the accompanying paper, B3FD data is shown to outperform other evaluated publicly available age estimation datasets (details in the referenced publication).

## Downloads

- **Images**
  - Archive: `B3FD_images.tar.gz` (≈ **5.73 GB**)
  - Download: [B3FD_images.tar.gz](https://ferhr-my.sharepoint.com/:u:/g/personal/kbr122017_fer_hr/EU4lr6xf_ZhBi9vN_i8h_XEB8aB1rCMGyZFGHAN55UHKIg?e=ahc9il)
  - MD5 checksum: `d492a8b7095cc1012b10dc978fb3c8f5`

- **Metadata**
  - Archive: `B3FD_metadata.tar.gz` (≈ **9.76 MB**)
  - Download: [B3FD_metadata.tar.gz](https://ferhr-my.sharepoint.com/:u:/g/personal/kbr122017_fer_hr/EcKiZtbTTb5Ep-fN32wCx4oBT8aQlsWhinBPfRhoZ9cGhQ?e=TukFyj)
  - MD5 checksum: `ece599dde9a5df2ccf7473a31816f418`

- **Filtration lists**
  - Archive: `B3FD_filtration_lists.tar.gz` (≈ **2.42 MB**)
  - Download: [B3FD_filtration_lists.tar.gz](https://ferhr-my.sharepoint.com/:u:/g/personal/kbr122017_fer_hr/EZfv3QcfwlFKjaESDBsMpbUB6uUWXS_15paxBh44nk8gmA?e=xqXy9p)
  - MD5 checksum: `0e27332f23babc23a15f4ee3bc9cb790`

## Usage & Licensing
- The images and labels are stated to be **publicly available for academic use**.  
- Refer to the GitHub repository and the linked paper for full licensing terms and citation requirements.

## Pricing
- **Free** for academic use (no pricing plans mentioned).