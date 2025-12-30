# All-Age-Faces Dataset

**Category:** Themed Directories  
**Type:** Public machine learning image dataset  
**Source:** [GitHub – All-Age-Faces Dataset](https://github.com/JingchunCheng/All-Age-Faces-Dataset)

## Overview
The All-Age-Faces (AAF) Dataset is a curated collection of 13,322 mostly Asian face images covering ages approximately 2 to 80. It is designed for machine learning research tasks such as age prediction and gender classification, and can also support face analysis across different age ranges.

## Features
- **Size and Composition**
  - 13,322 face images in total
  - Mostly Asian subjects
  - Age range: 2 to ~80 years
  - Gender distribution:
    - 7,381 female images
    - 5,941 male images
  - Each image contains a different individual (no identity repetition)

- **Data Organization**
  - `original images` folder: original face images
  - `key points` folder: facial landmark annotations
  - `aligned faces` folder: aligned face images based on landmarks
  - `example` folder: example of facial landmark distribution
  - `image sets` folder: train/validation split annotation files

- **File Naming Convention**
  - Image files named as: `%05dA%02d.jpg`
    - `person_id`: 5-digit serial number (00000–13321)
    - `age`: 2-digit age value
  - Gender by serial number range:
    - 00000–07380: female
    - 07381–13321: male

- **Annotations & Splits**
  - Each image is annotated with person ID, age, and gender
  - Standard random split into training and validation sets for fair comparison
  - Annotation line format in `image sets`:
    - `"%05dA%02d %d\n", person_id, age, gender`
    - `gender = 0` for female, `1` for male

- **Intended Use Cases**
  - Age prediction / age estimation
  - Gender classification
  - Face analysis across different ages
  - Research on facial landmarks and alignment-based methods

- **Access & Downloads**
  - Baidu link: https://pan.baidu.com/s/1WtHQsb73rLa-cZpBLi2dtg
  - Dropbox link: https://www.dropbox.com/s/a0lj1ddd54ns8qy/All-Age-Faces%20Dataset.zip?dl=0

- **Contact**
  - Maintainer: Jingchun Cheng  
    Email: chengjingchun [at] gmail [dot] com

- **Citation**
  - If used in research, cite:

    ```bibtex
    @article{cheng2019exploiting,
      title={Exploiting effective facial patches for robust gender recognition},
      author={Cheng, Jingchun and Li, Yali and Wang, Jilong and Yu, Le and Wang, Shengjin},
      journal={Tsinghua Science and Technology},
      volume={24},
      number={3},
      pages={333--345},
      year={2019},
      publisher={TUP}
    }
    ```

## Pricing
- The content does not specify any pricing; the dataset is presented as a public research dataset (check the repository for any license terms or usage conditions).
