## Overview

Awesome Feature Engineering provides resources for creating better features from raw data, a critical step that often determines machine learning model success.

## What is Feature Engineering?

The process of using domain knowledge to extract features from raw data via data mining techniques to improve machine learning algorithm performance.

## Core Techniques

### Numerical Features
- Scaling and normalization
- Binning/discretization
- Polynomial features
- Log transformations
- Power transformations

### Categorical Features
- One-hot encoding
- Label encoding
- Target encoding
- Frequency encoding
- Binary encoding

### Datetime Features
- Extracting components (year, month, day)
- Cyclical encoding (sin/cos)
- Time since events
- Holiday indicators

### Text Features
- TF-IDF
- Word embeddings
- N-grams
- Count vectorization
- Sentiment scores

### Image Features
- Color histograms
- Edge detection
- SIFT/SURF features
- Deep learning embeddings

## Advanced Methods

### Automated Feature Engineering
- Featuretools
- tsfresh (time series)
- AutoFeat
- Feature-engine

### Feature Selection
- Filter methods (correlation, mutual information)
- Wrapper methods (RFE)
- Embedded methods (L1 regularization)
- Importance-based selection

### Feature Interactions
- Polynomial interactions
- Ratio features
- Difference features
- Product features

## Domain-Specific

### Time Series
- Lag features
- Rolling statistics
- Seasonal decomposition
- Fourier features

### Geospatial
- Distance calculations
- Spatial aggregations
- Coordinate transformations
- Clustering-based features

## Tools & Libraries

- scikit-learn preprocessing
- pandas for data manipulation
- Featuretools for automated generation
- category_encoders for categorical encoding
- tsfresh for time series

## Best Practices

- Understand your data first
- Domain knowledge is crucial
- Avoid data leakage
- Cross-validate feature engineering
- Document transformations
- Monitor feature drift

## Evaluation

- Feature importance analysis
- A/B testing with/without features
- Learning curves
- Validation set performance