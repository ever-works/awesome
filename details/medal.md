# MeDAL

**Category:** Datasets  
**Tags:** datasets, healthcare, NLP

## Overview
MeDAL (Medical Abbreviation Disambiguation Library) is a large-scale medical text dataset created for abbreviation disambiguation and natural language understanding pre-training in the medical domain. It is associated with the paper **“MeDAL: Medical Abbreviation Disambiguation Dataset for Natural Language Understanding Pretraining.”**

## Features
- **Task focus:** Designed specifically for medical abbreviation disambiguation.
- **Domain:** Clinical and biomedical/medical text.
- **Primary use case:** Pre-training and evaluation for medical-domain NLP and NLU models.
- **Data scale:** Large medical text dataset (sized for pre-training applications).
- **Example structure:** Abbreviations in context mapped to their correct expanded medical forms (e.g., disambiguating “DHF” to “dihydrofolate” based on surrounding text).
- **Availability across platforms:**
  - Hugging Face Datasets (`medal`)
  - Kaggle (`medal-emnlp`)
  - Zenodo record for archival access
- **Code support:** Official GitHub repository with:
  - Data preprocessing scripts (`preprocess`)
  - Downstream task examples (`downstream`)
  - Example models and training scripts (`models`, `run.py`, `run.sh`)
  - Utility functions (`utils.py`)
  - Toy data for quick experimentation (`toy_data`)
- **Model resources:** Pre-trained ELECTRA model trained on MeDAL available on Hugging Face (`McGill-NLP/electra-medal`).
- **Research integration:**
  - Accompanied by peer-reviewed ACL paper and arXiv preprint.
  - Citation information provided via `CITATION.cff` and BibTeX.

## Access & Resources
- **Repository:** https://github.com/McGill-NLP/medal
- **Hugging Face dataset:** https://huggingface.co/datasets/medal
- **Kaggle dataset:** https://www.kaggle.com/xhlulu/medal-emnlp
- **Zenodo record:** https://zenodo.org/record/4265632
- **Paper (ACL):** https://www.aclweb.org/anthology/2020.clinicalnlp-1.15/
- **Paper (arXiv):** https://arxiv.org/abs/2012.13978
- **Pre-trained model:** https://huggingface.co/McGill-NLP/electra-medal

## Pricing
- Not specified in the available content. The dataset and code are hosted on public research and data platforms (GitHub, Hugging Face, Kaggle, Zenodo), which typically provide open access, but users should verify licensing and usage terms in the repository/published materials.