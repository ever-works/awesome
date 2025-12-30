# Violent-Flows Dataset

**Category:** Themed Directories  
**Type:** Research video dataset (crowd violence / non-violence)  
**Source:** http://www.openu.ac.il/home/hassner/data/violentflows/

---

## Overview
The Violent-Flows dataset is a collection of real-world crowd violence and non-violence video clips designed as a benchmark for violence detection research. It supports:
- Violent vs. non-violent video classification
- Violence outbreak detection in crowds

The dataset is commonly used in computer vision and video analysis research, particularly for behavior and anomaly detection in crowds.

---

## Dataset Details
- **Total videos:** 246
- **Source:** All videos downloaded from YouTube
- **Content type:** Real-world crowd scenes labeled as violent or non-violent
- **Clip duration:**
  - Shortest: 1.04 seconds
  - Longest: 6.52 seconds
  - Average: 3.60 seconds
- **Format:** Distributed as `Movies.zip` via FTP download (requires username and password)

---

## Features
- Benchmark for:
  - Binary classification (violent vs. non-violent)
  - Detection of violence onset in video sequences
- Standard protocols and results page to enable comparison between methods
- Companion feature descriptor:
  - **Violent Flows (ViF) descriptors** for real-time detection of violent crowd behavior
  - MATLAB code provided for feature extraction
- Research-ready materials:
  - Dataset
  - Example results and benchmarks
  - Reference paper with PDF and BibTeX

---

## Tools & Code
- **ViF feature extraction code:**
  - File: `violentflow_code.zip`
  - Main entry point: `VIF_create_feature_vec.m`
  - Usage: Call with path and filename of an AVI video
  - Output: Vector of VIF features representing the video

---

## Access & Download
- **Access procedure:**
  1. Fill out the online form to provide user details.  
     - Form: https://docs.google.com/forms/d/e/1FAIpQLSc6DEB9c84iatvuMIRVYf0tOTmGWFNaihAsM7Yc0JIMww7-Cw/viewform
  2. After submission, an FTP username and password are displayed.
  3. Use these credentials to download `Movies.zip` from:  
     - http://www.cslab.openu.ac.il/download/

---

## Results & Evaluation
- A dedicated **Results page** is provided to show and compare benchmark results:  
  - `results.html` (linked from the main dataset page)

---

## Citation
If you use the Violent-Flows dataset or its benchmark results, cite:

T. Hassner, Y. Itcher, and O. Kliper-Gross, *Violent Flows: Real-Time Detection of Violent Crowd Behavior,* 3rd IEEE International Workshop on Socially Intelligent Surveillance and Monitoring (SISM) at the IEEE Conference on Computer Vision and Pattern Recognition (CVPR), Rhode Island, June 2012.

- **Paper:** `violent_flows.pdf`
- **BibTeX:** `BibTeX.txt`

---

## Contact
- Tal Hassner – https://www.openu.ac.il/home/hassner  
- Yossi Itcher – yossi.itcher@gmail.com  
- Orit Kliper-Gross – orit.kliper@weizmann.ac.il

---

## Tags
- datasets
- video
- computer-vision