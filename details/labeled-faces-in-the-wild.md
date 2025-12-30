# Labeled Faces in the Wild

![Labeled Faces in the Wild](http://vis-www.cs.umass.edu/lfw/images/lfw_funneled.jpg)

## Overview
Labeled Faces in the Wild (LFW) is a widely used benchmark dataset for unconstrained face recognition research. It consists of thousands of labeled face images collected from the web and is considered a de facto standard test set for evaluating face verification and identification algorithms.

- **Type:** Dataset
- **Category:** Datasets
- **Domain:** Computer Vision, Machine Learning
- **Primary Task:** Face verification and face recognition in unconstrained settings
- **Provider / Origin:** University of Massachusetts Amherst
- **Official Site / Documentation:** http://vis-www.cs.umass.edu/lfw/

## Features
- **Dataset Scale**
  - Contains **more than 13,000 labeled facial images**.
  - Images correspond to **1,680 different people**.

- **Data Source & Collection**
  - Faces are **collected from the web**, reflecting natural, real-world image conditions.
  - Images are “in the wild” (unconstrained), rather than studio or controlled settings.

- **Task Orientation**
  - Designed primarily for **face verification** (deciding whether two images are of the same person).
  - Commonly used as a benchmark for **face identification** experiments as well.

- **Benchmark Status**
  - Described as the **de facto academic test set** for face verification.
  - Frequently used to report and compare performance of deep learning models (e.g., FaceNet).
  - Well-established in research literature and “awesome machine learning dataset” collections.

- **Typical Usage in Research**
  - Evaluation of **deep face embedding models** (e.g., FaceNet) via verification accuracy.
  - Threshold-based verification experiments where **Euclidean distance** between embeddings is used as a similarity measure.
  - Comparison and benchmarking of new face recognition systems and architectures.

## Example Benchmark Reference (from content)
- FaceNet reported:
  - **98.87% ± 0.15** accuracy on LFW in one setting.
  - **99.63% ± 0.09** accuracy on LFW in another setting.
  - An example optimal verification threshold around **1.24** (on embedding distance), illustrating common LFW usage.

## Tags
- datasets
- computer-vision
- machine-learning

## Pricing
- Not specified in the provided content. Refer to the official LFW website for license and access details.
