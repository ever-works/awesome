# RuFa Arabic Font Dataset

**Category:** Themed Directories  
**Tags:** datasets, computer-vision, fonts  
**Source:** [GitHub Release v0.1.0](https://github.com/mhmoodlan/arabic-font-classification/releases/tag/v0.1.0)

## Overview

RuFa is an Arabic font dataset focusing on images of Arabic text written in Ruqaa and Nastaliq-style (Farsi) fonts. It is part of an image-processing–oriented collection of datasets and is suitable for computer vision and font classification tasks.

## Features

- **Arabic text image dataset**
  - Contains images of Arabic text in Ruqaa and Farsi/Nastaliq-style fonts.
  - Designed for experiments in font and script classification, OCR preprocessing, and related computer vision tasks.

- **Directory structure & subsets (as listed for v0.1.0)**
  - `/rufa` — 40,516 images (main RuFa dataset).
  - `/real` — 516 images (real-world samples).
  - `/ruqaa` — 260 images (Ruqaa subset of real samples).
  - `/farsi` — 256 images (Farsi/Nastaliq subset of real samples).
  - `/synth` — 40,000 synthetic images in total, split into:
    - `/ruqaa` — 20,000 synthetic Ruqaa images.
    - `/farsi` — 20,000 synthetic Farsi images.

- **Additional metadata**
  - Further details about the dataset, labeling, and structure are provided in `RuFa-metadata.md` within the repository.

- **Related resources**
  - Release also includes a cleaned version of the CNN Arabic word list, useful for generating or analyzing Arabic word-level samples.

## Use Cases

- Training and evaluating Arabic font classification models.
- Research on Ruqaa vs. Farsi/Nastaliq font recognition.
- Benchmarking OCR or text detection pipelines on Arabic script.
- Synthetic vs. real-world domain adaptation experiments.

## Pricing

- The dataset is hosted on GitHub; no pricing information is provided in the available content (likely free/open for research and development use, subject to the repository’s license).