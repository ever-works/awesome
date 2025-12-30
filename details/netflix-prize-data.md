# Netflix Prize Data

**Category:** Datasets  
**Brand:** Netflix  
**Slug:** `netflix-prize-data`

## Overview
The Netflix Prize dataset is an anonymized collection of user–movie ratings originally released for the Netflix Prize competition, which challenged participants to improve Netflix’s recommendation accuracy. In this context, the dataset is made available to students via a public directory (`~bryce/cs63/labs/netflix/`) for use in machine learning projects and experiments, such as building and evaluating recommendation systems.

**Primary use cases:**
- Research and experimentation on recommender systems
- Course projects in machine learning
- Benchmarking collaborative filtering and related algorithms

## Source
- Course hosting page: https://www.cs.swarthmore.edu/~meeden/cs63/s16/lab10.html
- Mentioned additional contest sources for related datasets: Kaggle Competitions, ChaLearn challenges

## Features
- **Anonymized ratings data**  
  Contains movie rating records stripped of direct personal identifiers, suitable for educational and research use.

- **User–item interaction structure**  
  Data is organized as ratings given by users to movies, supporting standard recommendation tasks such as rating prediction and top‑N recommendation.

- **Large‑scale dataset**  
  Described as a large dataset typical of ML contests; intended to be stored on high‑capacity locations (e.g., `/scratch`) due to size considerations.

- **Competition‑proven benchmark**  
  Originally released for the Netflix Prize competition, making it a well‑known benchmark for collaborative filtering and recommendation algorithms.

- **Suitable for various ML algorithms**  
  Can be used with:
  - Custom implementations (e.g., from coursework)
  - Standard libraries such as scikit‑learn
  - A variety of methods, including matrix factorization, k‑nearest neighbors, and other recommendation approaches.

- **Educational integration**  
  Explicitly provided as an option for a course machine learning project, with students expected to:
  - Design their own ML challenge using the dataset
  - Implement and test models
  - Document methods and results (e.g., in LaTeX reports and READMEs).

## Typical Workflow (as implied by the context)
- Access dataset from the course public directory: `~bryce/cs63/labs/netflix/` (for Swarthmore CS63 environment).
- Store large data files under `/scratch` to avoid disk quota issues.
- Load and preprocess ratings for training/testing ML models.
- Use scikit‑learn or custom algorithms to build recommendation models.
- Evaluate prediction accuracy and document findings.

## Tags
- datasets  
- recommendation  
- machine-learning

## Pricing
The dataset is made available as a free resource in the context of the course; no pricing information or paid plans are indicated.