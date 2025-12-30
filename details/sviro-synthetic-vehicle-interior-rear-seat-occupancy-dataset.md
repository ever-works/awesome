# SVIRO – Synthetic Vehicle Interior Rear Seat Occupancy Dataset

**Category:** Datasets  
**Tags:** datasets, computer-vision, autonomous-driving  
**Source:** https://sviro.kl.dfki.de

## Overview
SVIRO (Synthetic Vehicle Interior Rear Seat Occupancy) is a synthetic dataset and benchmark for rear seat occupancy detection and classification in vehicle interiors. It comprises 25,000 synthetic scenes across ten different vehicles and is designed to evaluate machine learning models under controlled variation, focusing on generalization, robustness, and reliability when training data is limited.

A public benchmark and leaderboard are provided, with labels available for the test data.

## Main Dataset Features (SVIRO)
- **Scope & Size**
  - 25,000 synthetic rear-seat vehicle interior scenes
  - Ten different vehicle models
- **Intended Tasks**
  - Rear seat occupancy detection and classification
  - Object detection
  - Semantic and instance segmentation
  - Pose estimation
  - Evaluation of generalization and robustness under limited variation
- **Data Modalities**
  - RGB images
  - Simulated infrared (IR) images
  - Depth images
- **Annotations & Ground Truth**
  - Bounding boxes for object detection
  - Masks for semantic segmentation
  - Masks for instance segmentation
  - Keypoints for pose estimation
  - Per-seat images for seat-wise classification
- **Variation Design for Generalization**
  - Training data uses one set of backgrounds and textures; testing uses different ones
  - Different human models, child seats, and infant seats between training and test splits
  - Enables evaluation of:
    - Transfer from one vehicle interior to unseen vehicle interiors
    - Robustness to unseen intra-class variations
- **Benchmarking & Evaluation**
  - Public leaderboard to compare methods and models
  - Test labels available for detailed performance analysis

## Derived / Related Datasets

### SVIRO-Illumination
- **Purpose**: Study impact of changing illumination and environmental conditions on classification accuracy and robustness.
- **Vehicles**: 3 vehicle interiors.
- **Data Generation**:
  - For each vehicle: 250 training and 250 test scenes.
  - Each scene rendered under 10 different illumination and environmental conditions.
- **Use Cases**:
  - Illumination robustness analysis
  - Domain shift due to lighting changes

### SVIRO-NoCar
- **Purpose**: Learn invariance to background (dominant environment) while preserving foreground occupancy layout.
- **Data Setup**:
  - Humans, child seats, and infant seats positioned as if in a car interior.
  - Vehicle interior replaced with randomly selected HDR background images.
  - Input-target pairs: same foreground scene with different backgrounds to promote background invariance.
- **Size**:
  - 2,938 training scenes
  - 2,981 test scenes
  - Each scene rendered with 10 different backgrounds.
- **Use Cases**:
  - Background invariance learning on synthetic data
  - Transfer of learned invariances from synthetic to real images

### SVIRO-Uncertainty
- **Purpose**: Evaluate and develop methods that provide predictive uncertainty in safety-critical applications.
- **Task**:
  - For each of the 3 rear seat positions, classify the occupying object (including empty as a valid class).
- **Datasets**:
  1. Training set with adult passengers only
     - 4,384 sceneries
     - 8 classes
  2. Training set with adults, child seats, and infant seats
     - 3,515 samples
     - 64 classes
- **Evaluation**:
  - Fine-grained test sets at multiple difficulty levels for assessing model reliability and uncertainty behavior.

### SVIRO-InterCar
- **Purpose**: Study robustness and generalization across different vehicle interiors and viewpoints.
- **Variation Strategy**:
  - Similar to SVIRO-Illumination but varying the **vehicle interior** instead of illumination.
  - Each scenery generated multiple times with different car interiors.
  - Perspective adapted to each vehicle; window differences also induce illumination changes.
- **Versions**:
  - Version with adult occupants only: 1,000 sceneries.
  - Version with adults and infants in infant seats (partial description; total size not fully specified in provided text).

## Use Cases
- Training and benchmarking models for:
  - Rear seat occupancy detection and classification
  - Robustness to unseen interiors, backgrounds, and lighting
  - Background and illumination invariance
  - Uncertainty estimation and reliability analysis in safety-critical automotive scenarios

## Pricing
No pricing information is provided in the available content. The dataset appears to be a research/benchmark resource; access details should be checked on the official website.