# Prostate-MRI

**Category:** Themed Directories  
**Tags:** datasets, medical-imaging, health  
**Source:** [The Cancer Imaging Archive – Prostate-MRI Collection](https://wiki.cancerimagingarchive.net/display/Public/Prostate-MRI)

## Description
Prostate-MRI is a public medical imaging dataset of prostate Magnetic Resonance Images collected at 3T using an endorectal and phased array surface coil (Philips Achieva). All patients had biopsy-confirmed prostate cancer and underwent robotic-assisted radical prostatectomy. Custom molds were generated from each MRI so that prostatectomy specimens could be sliced in the same plane as the MRI, enabling detailed radiology–pathology correlation. Data was generated at the National Cancer Institute (Bethesda, Maryland, USA) between 2008–2010.

The collection is part of The Cancer Imaging Archive (TCIA) and is suitable for research in prostate cancer imaging, computational modeling, and algorithm evaluation.

## Features

### Imaging and Clinical Characteristics
- Prostate MRIs acquired at 3T (Philips Achieva).
- Use of both endorectal coil and phased array surface coil for imaging.
- All cases have:
  - Biopsy-confirmed prostate cancer.
  - Robotic-assisted radical prostatectomy performed.
- A patient-specific mold is generated from each MRI.
- Prostatectomy specimens are placed in the mold and cut in the same plane as the MRI for precise alignment of histopathology with imaging.
- Data timeframe: collected between 2008–2010.

### Data Modalities and Formats
- **Images (DICOM)**
  - Prostate MRI scans.
  - Total size: ~3.2 GB.
  - Format: DICOM.
  - Accessible via bulk download or searchable interface (TCIA NBIA search).
- **Histopathology Images (JPEG)**
  - Corresponding histopathology images from prostatectomy specimens.
  - Total size: ~206 MB.
  - Format: JPEG.
  - Accessible via direct download package or searchable interface (TCIA Pathology Portal / PathDB).

### Access and Tooling
- **MRI DICOM images**
  - Bulk download via TCIA (.tcia package).
  - Query and filter via NBIA Search: `CollectionCriteria=PROSTATE-MRI`.
  - Download requires the **NBIA Data Retriever** client.
- **Histopathology JPEG images**
  - Bulk download as a faspex package via the TCIA Aspera server.
  - Searchable through the PathDB interface with collection filter `prostate_mri`.
  - Download requires installation of the **IBM Aspera Connect** browser plugin.

### Licensing and Usage
- All provided data (MRI DICOM and histopathology JPEGs) is distributed under the **Creative Commons Attribution 3.0 (CC BY 3.0)** license.
- Data may be reused, shared, and adapted with appropriate attribution to the source.

### Integration with Broader Resources
- Linked with the **NCI Cancer Research Data Commons (CRDC)**, which offers:
  - Additional related cancer research data.
  - Cloud-based data science infrastructure.
  - Integration of datasets with analytic tools for sharing, integration, and analysis.

## Data Access Links
- **Collection DOI / Main Landing Page:**  
  <https://doi.org/10.7937/K9/TCIA.2016.6046GUDv>

- **MRI (DICOM, ~3.2 GB):**  
  - Download: [TCIA .tcia package](https://wiki.cancerimagingarchive.net/download/attachments/3277260/PROSTATE-MRI-5-18-2018-doiJNLP-dKJJAqnS.tcia?version=1&modificationDate=1534786953393&api=v2)  
  - Search/Filter: [NBIA Search – PROSTATE-MRI](https://www.cancerimagingarchive.net/nbia-search/?CollectionCriteria=PROSTATE-MRI)

- **Histopathology (JPEG, ~206 MB):**  
  - Download: [Aspera faspex package](https://faspex.cancerimagingarchive.net/aspera/faspex?context=eyJyZXNvdXJjZSI6InBhY2thZ2VzIiwidHlwZSI6ImV4dGVybmFsX2Rvd25sb2FkX3BhY2thZ2UiLCJpZCI6IjU1NiIsInBhc3Njb2RlIjoiNjBhNDEwNzIyZTczODkzOTE0MjEzNjUxZGI2OWExOGM0MWM5MDY1NiIsInBhY2thZ2VfaWQiOiI1NTYiLCJlbWFpbCI6ImhlbHBAY2FuY2VyaW1hZ2luZ2FyY2hpdmUubmV0In0=)  
  - Search/Filter: [PathDB Search – prostate_mri](https://pathdb.cancerimagingarchive.net/imagesearch?f[0]=collection:prostate_mri)

## Licensing
- **License:** [Creative Commons Attribution 3.0 (CC BY 3.0)](https://creativecommons.org/licenses/by/3.0/)

## Pricing
- Access to this dataset is **free** under the CC BY 3.0 license; no paid plans are indicated.
