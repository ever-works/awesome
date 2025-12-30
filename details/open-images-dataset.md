# Open Images Dataset

A large-scale image dataset from Google with millions of images, bounding boxes, segmentation masks, visual relationships, and image-level labels, widely used in computer vision research and applications.

- **Website**: https://storage.googleapis.com/openimages/web/download.html  
- **Provider**: Google  
- **Category**: Themed directories → Datasets / Computer Vision / Images

---

## Features

### Dataset Structure
- **Subset with bounding boxes (600 classes)**
  - Images annotated with object bounding boxes.
  - Includes:
    - Object segmentations (instance masks)
    - Visual relationships
    - Localized narratives

- **Subset with image-level labels (19,958 classes)**
  - Image-level annotations spanning 19,958 classes.

- **Complete Open Images**
  - Full dataset combining images and multiple annotation types.

- **Open Images Extended**
  - Additional supplementary data beyond the core dataset.

### Access and Download
- **Download via FiftyOne**
  - Supports direct download and visualization using the FiftyOne toolkit.

- **Manual download**
  - **Images**
    - Images downloadable by split and image ID:
      - `$SPLIT/$IMAGE_ID`
      - Placeholders: `$SPLIT`, `$IMAGE_ID`.
  - **Annotations and metadata**
    - Separate files for train, validation, and test.
    - Segmentations split into **16 smaller files per split**, grouped by the first character of `ImageID` for easier download.

- **Known corrections**
  - On Jan 27th 2021, two entries were removed from the visual relationships train file `oidv6-train-annotations-vrd.csv` because they referenced image `634483a6a8a74df4`, which is not in the bounding-box-annotated set.

### Annotations and Data Formats

#### Bounding Boxes
- Stored as CSV; each row defines **one bounding box**.
- Example header:
  ```
  ImageID,Source,LabelName,Confidence,XMin,XMax,YMin,YMax,
  IsOccluded,IsTruncated,IsGroupOf,IsDepiction,IsInside,
  XClick1X,XClick2X,XClick3X,XClick4X,XClick1Y,XClick2Y,XClick3Y,XClick4Y
  ```
- **Fields**:
  - `ImageID`: Identifier of the image.
  - `Source`: Annotation source (e.g., `xclick`, `activemil`).
  - `LabelName`: Class label identifier.
  - `Confidence`: Confidence score for the box.
  - `XMin`, `XMax`, `YMin`, `YMax`: Normalized box coordinates.
  - `IsOccluded`: 1 present, 0 not present, -1 unknown.
  - `IsTruncated`: 1 present, 0 not present, -1 unknown.
  - `IsGroupOf`: 1 present, 0 not present, -1 unknown.
  - `IsDepiction`: 1 present, 0 not present, -1 unknown.
  - `IsInside`: 1 present, 0 not present, -1 unknown.
  - `XClick1X` … `XClick4X`: X-coordinates of click points used for annotation.
  - `XClick1Y` … `XClick4Y`: Y-coordinates of click points used for annotation.

#### Instance Segmentation Masks
- **Mask images**
  - PNG binary images.
  - Non-zero pixels: belong to a single object instance.
  - Zero pixels: background.
  - Example filenames:
    - `e88da03f2d80f1a1_m019jd_e16d01b9.png`
    - `540c5536e95a3282_m014j1m_b00fa52e.png`
    - `1c84bdd61fa3b883_m06m11_62ef2388.png`
    - `663389d2c9d562d8_m04_sv_7e23f2a5.png`
    - `072b8fd82919ab3e_m06mf6_dd70f221.png`

- **Archive structure**
  - Masks distributed in zip archives named:
    - `<subset>_<suffix>.zip`
  - Each archive contains all masks for images whose `ImageID` starts with `<suffix>`.
  - `<suffix>` ranges from `0–9` and `a–f`.

- **`masks_data.csv`**
  - Each row describes **one instance mask**.
  - Example header:
    ```
    MaskPath,ImageID,LabelName,BoxID,BoxXMin,BoxXMax,BoxYMin,BoxYMax,PredictedIoU,Clicks
    ```
  - Fields:
    - `MaskPath`: Relative path to the PNG mask file.
    - `ImageID`: Corresponding image ID.
    - `LabelName`: Class label for the instance.
    - `BoxID`: Identifier of the associated bounding box.
    - `BoxXMin`, `BoxXMax`, `BoxYMin`, `BoxYMax`: Normalized coordinates of the parent box.
    - `PredictedIoU`: Predicted intersection-over-union quality for the mask.
    - `Clicks`: Encoded list of click data (each entry contains coordinates and flags).

### Visual Relationships and Localized Narratives
- Visual relationship annotations available (e.g., subject–predicate–object relations) via `oidv6-train-annotations-vrd.csv` and related files.
- Localized narratives provided for the subset with bounding boxes, connecting natural language descriptions with image regions.

---

## Pricing

- Not specified in the provided content. The dataset is typically offered as a freely downloadable research resource; confirm any usage terms or licenses directly on the official site.
