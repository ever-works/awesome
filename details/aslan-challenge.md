# ASLAN Challenge

**Category:** Themed Directories  
**Type:** Video action similarity dataset and benchmark  
**Brand:** Open University of Israel  
**Source:** <http://www.openu.ac.il/home/hassner/data/ASLAN/ASLAN.html>

## Overview

The Action Similarity Labeling (ASLAN) Challenge is a video database and benchmark designed to study action similarity in unconstrained videos. It provides a labeled dataset of action samples and a full testing protocol for evaluating methods that determine whether two video clips contain the same action.

## Features

- **Dataset Composition**
  - 3,697 action samples
  - 1,571 unique YouTube video URLs
  - 432 action classes (non-trivial categories)
  - 316 classes with more than one sample
  - Average of 8.5 samples per class
  - Largest class: **“Handstand”** with 91 samples from 64 URLs
  - 71 long samples (duration > 10 seconds)
  - 187 short samples (duration < 1 second)

- **Action Samples**
  - Each sample is a sub-sequence of a shot from a single camera
  - Each sample contains one detected action in a consecutive set of frames
  - Manually labeled with the name of the action being performed

- **Benchmark Protocol**
  - Binary pair matching task: decide if two videos present the **same** or **not-same** action
  - Training uses labeled video pairs (same / not-same)
  - Action classes present in the test set are **not** included in training
    - Prevents building explicit action models for test actions during training
    - Encourages generalization to unseen actions

- **Provided Resources**
  - Full ASLAN video database
  - Public benchmark protocols for evaluation
  - Descriptor encodings of action samples using state-of-the-art methods (at time of creation)

- **Research Use and Access**
  - Intended for video understanding and action similarity research
  - Dataset and related materials are made publicly available for the research community
  - Use is subject to original copyright holders’ terms; redistribution may require explicit permission

- **Related Event**
  - Associated with the 1st IEEE International Workshop on Action Similarity in Unconstrained Videos (ACTS'13), held with CVPR 2013, which used ASLAN as a performance competition benchmark.

## Tags

- Video
- Machine Learning
- Datasets

## Pricing

No pricing information is provided in the available content; the dataset and benchmark are described as publicly available for research use, subject to copyright and usage terms.