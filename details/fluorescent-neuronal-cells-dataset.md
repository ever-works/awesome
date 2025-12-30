# Fluorescent Neuronal Cells Dataset

**Category:** Themed Directories  
**Tags:** datasets, neuroscience, computer-vision  
**Provider:** Alma Mater Studiorum – Università di Bologna  
**Source:** [Dataset page and download](http://amsacta.unibo.it/id/eprint/6706)

> An image dataset of fluorescent neuronal cells intended as a testbed for developing and benchmarking machine learning and image analysis methods in neuroscience.

---

## Overview

The Fluorescent Neuronal Cells dataset is a collection of high-resolution fluorescence microscopy images of mice brain slices. It is designed as a benchmark and testbed for computer vision and deep learning methods applied to biomedical imaging, especially for tasks involving neuronal cell detection and counting.

A newer version of this dataset is available: [alternative version link](https://amsacta.unibo.it/id/eprint/7347/).

---

## Features

- **Domain & Purpose**
  - Focus on **biological imaging** rather than natural images.
  - Intended to **benchmark and develop** computer vision and deep learning methods in neuroscience and biomedical imaging.
  - Aims to support:
    - Research in **biomedical-related fields**, where popular pre-trained models often perform poorly.
    - **Methodological research in deep learning**, addressing the specific requirements of fluorescence microscopy images.

- **Data Contents**
  - **283 images** of fluorescent neuronal cells.
  - Images are **high-resolution**: **1600 × 1200 pixels** each.
  - Images depict **mice brain slices** acquired by **fluorescence microscopy**.
  - Neurons are **highlighted with a yellow marker**: **Cholera Toxin sub-unit b (CTb)**.

- **Annotations / Ground Truth**
  - Pixel-wise segmentation labels for stained neurons.
  - Ground-truth masks are **black-and-white images**:
    - Background: pixel value **0 (black)**.
    - Neurons: pixel value **255 (white)**.
  - Labels generated via a **hybrid approach** combining:
    - **Semi-automatic** semantic segmentation.
    - **Manual** semantic segmentation.

- **Potential Applications**
  - **Semantic segmentation** of neurons.
  - **Object detection** of neuronal cells.
  - **Object counting / cell counting**.
  - General benchmarking for **deep learning in microscopy and neuroscience**.

- **File & Access Details**
  - Distributed as a compressed archive: `fluocells.zip`.
  - Approximate size: **414 MB**.
  - Direct download: `https://amsacta.unibo.it/id/eprint/6706/1/fluocells.zip`.

- **Licensing & Usage**
  - Licensed under **Creative Commons Attribution – ShareAlike 4.0 (CC BY-SA 4.0)**.  
    License details: http://creativecommons.org/licenses/by-sa/4.0/

- **Related Publication**
  - Morelli, R. et al., 2021. *Automating cell counting in fluorescent microscopy through deep learning with c-ResUnet.* Scientific Reports.  
    DOI: https://doi.org/10.1038/s41598-021-01929-5

- **Funding Acknowledgments**
  - University of Bologna (RFO 2018).
  - European Space Agency (Research agreement collaboration 4000123556).

---

## Authors / Contributors

Affiliation for all listed authors: **University of Bologna**.

- Luca Clissa – ORCID: [0000-0002-4876-5200](http://orcid.org/0000-0002-4876-5200)
- Roberto Morelli – ORCID: [0000-0001-5090-9026](http://orcid.org/0000-0001-5090-9026)
- Fabio Squarcio – ORCID: [0000-0002-6033-1042](http://orcid.org/0000-0002-6033-1042)
- Timna Hitrec – ORCID: [0000-0002-9296-3482](http://orcid.org/0000-0002-9296-3482)
- Marco Luppi – ORCID: [0000-0002-9462-5014](http://orcid.org/0000-0002-9462-5014)
- Lorenzo Rinaldi – ORCID: [0000-0001-9608-9940](http://orcid.org/0000-0001-9608-9940)
- Matteo Cerri – ORCID: [0000-0003-3556-305X](http://orcid.org/0000-0003-3556-305X)
- Roberto Amici – ORCID: [0000-0002-9692-2215](http://orcid.org/0000-0002-9692-2215)
- Stefano Bastianini – ORCID: [0000-0003-2468-1704](http://orcid.org/0000-0003-2468-1704)
- Chiara Berteotti – ORCID: [0000-0002-4143-9445](http://orcid.org/0000-0002-4143-9445)
- Viviana Lo Martire – ORCID: [0000-0001-8696-0835](http://orcid.org/0000-0001-8696-0835)
- Davide Martelli – ORCID: [0000-0001-6523-9598](http://orcid.org/0000-0001-6523-9598)

*(Author list is truncated in the provided content; see the source page for the complete list if needed.)*

---

## Pricing

- **Cost:** Free to download and use under the **CC BY-SA 4.0** license.

---

## Additional Notes

- This dataset is included in curated lists of **machine learning datasets**, emphasizing its usefulness as a benchmark for deep learning in biomedical imaging.
- Users are encouraged to cite the associated Scientific Reports paper when using the dataset in academic work.