# QIN-PROSTATE

A Quantitative Imaging Network (QIN) prostate MRI collection hosted on The Cancer Imaging Archive (TCIA), aimed at quantitative imaging research and algorithm development for prostate cancer.

---

## Overview

- **Domain:** Prostate cancer imaging
- **Modality:** Multiparametric MRI (mpMRI)
- **Use cases:**
  - Quantitative imaging research
  - Algorithm development and validation
  - Prostate cancer detection, staging, and characterization
- **Provider:** Brigham and Women’s Hospital (PI: Dr. Fiona Fennessy)
- **Platform:** The Cancer Imaging Archive (TCIA)

---

## Data Access

- **Access method:**
  - Requires a **TCIA account**
  - After account creation, email **help@cancerimagingarchive.net** to request access
- **Download tools:**
  - Uses the **NBIA Data Retriever** for downloading images
- **License / Restrictions:**
  - **TCIA restricted** data
- **Data format:**
  - DICOM images
  - Approx. **4.4 GB**

---

## Collection Statistics

- **Modality:** MR
- **Number of participants:** 22
- **Number of studies:** 22
- **Number of series:** 319
- **Number of images:** 25,981
- **Total image size:** 4.4 GB

---

## Imaging Protocol & Technical Details

All exams were performed on a **GE Signa HDx 3.0T** MR scanner (GE Healthcare, Waukesha, WI) using:

- **Coils:**
  - 8-channel abdominal array
  - Endorectal coil (Medrad, Pittsburgh, PA)

### MR Sequences

1. **T1-weighted imaging**
   - Sequence: Spoiled Gradient Recalled Echo (SPGR)
   - Parameters: TR/TE/flip angle = **385 ms / 6.2 ms / 65°**
   - Field of view (FOV): **(16 cm)²**

2. **T2-weighted imaging**
   - Sequence: Fast Recovery Fast Spin Echo (FRFSE)
   - Parameters: TR/TE = **3500 / 102 ms**
   - FOV: **(16 cm)²**

3. **Diffusion-Weighted (DW) imaging**
   - Sequence: Echo planar imaging with trace diffusion sensitization
   - b-values: **0 and 500 s/mm²**
   - Parameters: TR/TE = **2500 / 65 ms**
   - Outputs: Data suitable for calculating **Apparent Diffusion Coefficient (ADC) maps**

4. **Dynamic Contrast-Enhanced (DCE) MRI**
   - Sequence: 3D SPGR
   - Parameters: TR/TE/flip angle = **3.6 ms / 1.3 ms / 15°**
   - FOV: **(26 cm)²**
   - Coverage: Full prostate gland
   - Reconstructed voxel size: **1 × 1 × 6 mm** (interpolated to 256 × 256 matrix)
   - Temporal resolution:
     - Frames acquired at ~5 s intervals
     - Number of frames varied between **12 and 16 slices**, resulting in time resolution ~**4.4–5.3 seconds**

### Contrast Agent Protocol (for DCE MRI)

- Agent: **Gadopentetate dimeglumine (Magnevist)**
- Dose: **0.15 mmol/kg**
- Delivery: Intravenous, syringe pump
  - Injection rate: **3 ml/s**
  - Followed by **20 ml saline flush** at same rate
- Baseline imaging: ~**5 baseline scans** prior to contrast injection to estimate baseline tissue properties

---

## Intended Use & Research Context

- **Primary purpose:**
  - Provide clinical mpMRI data for development and evaluation of **quantitative methods** for prostate cancer characterization
- **Applications include:**
  - Detection and/or staging of prostate cancer
  - Quantitative analysis methods (e.g., DCE-MRI parameter estimation, ADC analysis)
- A subset of these datasets was used in published research (e.g., Fedorov et al., 2014) comparing methods for estimating DCE-MRI parameters.

---

## Related Programs

### NCI Quantitative Imaging Network (QIN)

- **Mission:**
  - Improve the role of quantitative imaging in oncology decision-making
  - Develop and validate data acquisition methods, analysis tools, and software
  - Support tailoring treatment to individual patients and predicting/monitoring response to drug or radiation therapy
- More information: QIN collections are summarized on the **Quantitative Imaging Network Collections** page at NCI/TCIA.

---

## Features

- Multiparametric prostate MRI (T1, T2, DW, DCE)
- High-field **3.0T** imaging with combined endorectal and phased array coils
- Detailed acquisition parameters suitable for quantitative and reproducible research
- DWI with b=0 and 500 s/mm², enabling ADC map computation
- DCE MRI with high temporal resolution and full prostate coverage
- Prostate cancer–focused, clinically acquired data
- Standard medical imaging format (**DICOM**)
- Curated and hosted within TCIA under the NCI QIN framework

---

## Pricing

- No explicit pricing information is provided in the available content. Access is through TCIA under a restricted-use model; terms may apply via TCIA’s standard access and licensing policies.