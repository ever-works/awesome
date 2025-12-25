# Awesome Neuroimaging

**Description**  
Curated directory of software tools and resources for exploring, organizing, and analyzing brain images and recordings, with a focus on magnetic resonance (MR) neuroimaging.

**Source**  
<https://github.com/NPACore/awesome-neuroimaging#readme>

---

## Features

### Scope
- Focus on neuroimaging of living subjects, especially MR-based data.
- Includes tools for both brain images and electrophysiological recordings.
- Emphasis on analysis workflows, data organization, and quality assurance.

### Viewers
- **wb_view** – Tool for viewing neuroimaging data (part of the listed ecosystem of viewers).

### Acquisition
- **MR**
  - **Organization** – Category for tools dealing with organizing MR acquisition data.
  - **Management** – Category for tools and scripts related to managing MR datasets and sessions.
  - **Motion**
    - `Dimon` – Tool focused on motion-related handling/processing in MR acquisitions.

### Quality Assurance and Checking
- **QA and QC of scanner images** – Category for tools and workflows that check and monitor the quality of scanner output and acquired images.

### Pipelines
- **Preprocessing workflows** – Collection of tools and scripts to perform common preprocessing steps.
- **Suites** – Comprehensive software packages for multiple imaging modalities, often including graphical user interfaces.
- **BOLD**
  - `afni_proc.py` – Pipeline tool for preprocessing BOLD fMRI data.
- **DSI** – Category placeholder for diffusion spectrum imaging pipelines.
- **Structural** – Category placeholder for structural MRI preprocessing pipelines.

### Raw Data
- Tools for handling raw scanner output, including DICOM and k-space data:
  - `pydicom` – Python library for working with DICOM files.
  - `dicom_hinfo` – Utility for extracting header information from DICOM files.
  - `dicom_hdr` – Tool for inspecting DICOM headers.
  - `dcmdirtab` – Utility related to organizing or listing DICOM directories.
  - `dcmtab_bids` – Tool for mapping/organizing DICOM data into BIDS-like structures.

### Provenance and Automation
- Tools and patterns for recording data lineage and automating workflows:
  - `Makefile` – Use of Makefiles for reproducible, scripted processing.
  - `datalad run --input=... --output=...` – Command pattern for reproducible, version-controlled execution with DataLad.
  - `3dNotes` – Tool for embedding or managing notes/metadata in imaging datasets.
  - `niinote` – Utility for attaching or handling notes and provenance in NIfTI or related files.

### Imaging Tools
Software to read, write, and manipulate volumetric and surface neuroimaging data.

#### Skullstripping
- `3dSkullStrip` – Tool for removing non-brain tissue from MR images.
- `bet` – Brain extraction utility for skull stripping.
- `antsBrainExtraction.sh` – ANTs-based brain extraction script.
- `mri-watershed` – Tool using watershed algorithms for brain extraction.

#### Warping
- Spatial normalization tools and workflows for aligning images to templates.
  - **Templates** – Category for reference templates and related resources.

#### Manipulation
- Tools for performing mathematical operations and transformations on image matrices and voxel values.

#### Modeling
- **HRF** – Category for hemodynamic response function modeling tools.
- **MRSI** – Category for MR spectroscopic imaging modeling tools.
- **EEG**
  - `fooof` – Tool for parametrizing neural power spectra (useful for EEG/MEG analyses).
- **Misc** – Miscellaneous modeling tools that do not fit other subcategories.

### Libraries

#### Python
- `nibabel` – Library for reading and writing common neuroimaging file formats.
- `nipype` – Framework for building and running neuroimaging analysis pipelines.
- `nilearn` – Python library for statistical learning and decoding on neuroimaging data.

#### R
- Category placeholder for R-based neuroimaging libraries.

#### MATLAB
- `imtool3D_td` – MATLAB-based 3D image viewing and manipulation tool.

### Resources
- General resource section (e.g., documentation, examples, educational materials) related to neuroimaging tools and practices.

---

## Category
- Themed directory / Awesome list for neuroimaging tools.

## Tags
- Scientific computing  
- Data science  
- Research

## Pricing
- Not applicable (open, curated list of tools and resources).