# QIN-PROSTATE-Repeatability

**Category:** Themed Directories  
**Type:** Medical imaging research dataset (prostate mpMRI, test–retest)

## Overview
QIN-PROSTATE-Repeatability is a multiparametric prostate MRI (mpMRI) dataset collected in a test–retest setting to study the repeatability and robustness of MRI-based measurements in prostate cancer. It addresses the limited availability of repeatability data for prostate mpMRI, which is important for validating mpMRI as an imaging biomarker in prostate cancer.

- **Cancer type:** Confirmed or suspected prostate cancer  
- **Primary use:** Quantitative imaging, test–retest repeatability analysis, biomarker robustness studies in prostate MRI  
- **Data source institution:** Brigham and Women’s Hospital  
- **Access via:** The Cancer Imaging Archive (TCIA)

## Source
- **Primary collection page:** https://www.cancerimagingarchive.net/collection/qin-prostate-repeatability/
- **Original TCIA wiki entry (redirect):** https://wiki.cancerimagingarchive.net/display/Public/QIN-PROSTATE-Repeatability

## Features

### Imaging Data
- Multiparametric prostate MRI (mpMRI) acquired in a **test–retest** design.  
- **Field strength:** 3 Tesla for all imaging studies.  
- **Protocols:** Standard prostate mpMRI protocol at Brigham and Women’s Hospital, with consistent protocol settings targeted between baseline and repeat scans.
- **Temporal design:** Baseline and repeat examinations acquired within **2 weeks** of each other.

### MRI Sequences Included
- **T2-weighted imaging**
- **Diffusion-Weighted Imaging (DWI):**
  - b-values: **0** and **1400 mm/s²**
  - Derived **Apparent Diffusion Coefficient (ADC)** maps generated using scanner software
- **Dynamic Contrast-Enhanced (DCE) MRI:**
  - Includes **DCE subtract (SUB) maps**, computed as the difference between the phase at contrast bolus arrival and the baseline phase

### Scanner and Hardware Details
- All examinations performed at **3T**.
- **Scanner platforms and software:**
  - 6 patients: **GE Signa HDxt**, software release **15.0_M4A_097.a**
  - 7 patients: **GE Discovery MR750w**, software release **DV24.0_R01_1344**
- **Coil setup:** Transrectal coil within an air-filled balloon (Medrad Inc., Warrendale, PA) used in all imaging studies.
- Effort made to maintain **same scanner hardware and software configuration** and similar protocol settings between baseline and repeat exams for each patient.

### Derived and Structured Data
- **Segmentations:**
  - Provided as **DICOM Segmentation** images.
- **Segmentation-based measurements:**
  - Provided as **DICOM Structured Reports (SR)** following **DICOM SR TID 1500**.
- Data representation follows standard DICOM mechanisms, with tooling available for conversion and visualization (described in referenced publications).

### Planned / Future Additions (as stated in source)
- **Parametric maps** derived from analysis (to be shared in DICOM format).
- Potential addition of **clinical data**, pending IRB clearance:
  - Demographics
  - PSA levels
  - Pathology sampling data (e.g., biopsy Gleason scores)

## Research Context & Funding
- Focused on **repeatability** of prostate mpMRI, which is critical for establishing technical characteristics of mpMRI as an **imaging biomarker** for prostate cancer.
- **Data collection support:** U01 CA151261 (PI: Fiona Fennessy)
- **Data preparation for public sharing:** U24 CA180918 (QIICR, http://qiicr.org; MPI: Andrey Fedorov and Ron Kikinis)

## Pricing
- Not specified in the provided content. (TCIA collections are typically publicly accessible for research use; check the collection page for any current access conditions.)

## Tags
- Datasets  
- Medical imaging  
- Prostate MRI  
- Quantitative imaging  
- Test–retest / repeatability  
- Research