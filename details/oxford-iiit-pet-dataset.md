# Oxford-IIIT Pet Dataset

**Category:** Themed Directories  
**Tags:** computer-vision, images, datasets  
**Source:** http://www.robots.ox.ac.uk/~vgg/data/pets/

## Overview
The Oxford-IIIT Pet Dataset is a collection of pet images (cats and dogs) covering 37 categories (breeds), with roughly 200 images per class. The images exhibit large variations in scale, pose, and lighting. Each image is accompanied by detailed ground-truth annotations suitable for computer vision tasks such as classification, detection, and segmentation.

## Features
- **Content & Classes**
  - 37 pet categories (cat and dog breeds).
  - Approximately 200 images per breed.
  - Focus on natural variations in scale, pose, and illumination.

- **Annotations (per image)**
  - Species and breed label.
  - Tight bounding box / region of interest (ROI) around the animal’s head.
  - Pixel-level foreground–background segmentation (trimap).

- **Data Format & Size**
  - Total size ~800 MB (images + annotations).
  - Distributed as:
    - `images.tar.gz` — image files.
    - `annotations.tar.gz` — ground truth data.

- **Use Cases**
  - Image classification (species and breed recognition).
  - Object detection (head ROI localization).
  - Semantic / trimap segmentation (foreground vs background).
  - Benchmarking and training for academic and commercial computer vision.

- **Access & Distribution**
  - Available via Academic Torrents (BitTorrent) as a combined dataset + ground-truth torrent.
  - Also downloadable over HTTP as separate archives for images and annotations.

- **Documentation & References**
  - Associated with the publication:
    - O. M. Parkhi, A. Vedaldi, A. Zisserman, C. V. Jawahar, IEEE Conference on Computer Vision and Pattern Recognition (CVPR), 2012.
  - Example annotation visualizations provided (breed labels, head ROIs, trimap segmentations).

## Licensing
- Licensed under **Creative Commons Attribution-ShareAlike 4.0 International (CC BY-SA 4.0)**.
- May be used for **commercial and research purposes** under the terms of this license.
- Copyright remains with the original image owners.

## Pricing
- No pricing information is provided; the dataset is distributed under CC BY-SA 4.0 and is available for download without listed fees.
