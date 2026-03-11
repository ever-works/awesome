## Overview

Awesome OCR curates the best optical character recognition projects, tools, and resources for extracting text from images, PDFs, and scanned documents.

## OCR Engines

### Tesseract OCR
- **Tesseract**: Google's powerful open-source OCR engine supporting 100+ languages
- Originally developed by HP, now maintained by Google
- Supports multiple image formats
- Trainable for custom fonts and languages
- Command-line and API interfaces

### Deep Learning-Based OCR
- **EasyOCR**: Deep learning-based OCR supporting 80+ languages
- **PaddleOCR**: Practical ultra-lightweight OCR system by Baidu
- **MMOCR**: Comprehensive text detection and recognition toolbox
- **TrOCR**: Transformer-based OCR from Microsoft
- **Doctr**: Document Text Recognition from Mindee

### Commercial OCR Services
- **Google Cloud Vision API**: Cloud-based OCR with high accuracy
- **AWS Textract**: Extract text and data from documents
- **Azure Computer Vision**: Microsoft's OCR service
- **ABBYY FineReader**: Enterprise OCR solution

## Language Wrappers and Libraries

### Python
- **pytesseract**: Python wrapper for Tesseract
- **pyocr**: Python wrapper for Tesseract and Cuneiform
- **EasyOCR**: Ready-to-use OCR with 80+ languages
- **OCRmyPDF**: Add OCR text layer to scanned PDFs
- **DocTR**: End-to-end OCR for documents

### JavaScript/Node.js
- **tesseract.js**: Pure JavaScript OCR
- **node-tesseract-ocr**: Node.js wrapper for Tesseract
- **OCR.space API**: Simple REST API for OCR

### Go
- **gosseract**: Go wrapper for Tesseract OCR
- Native Go implementations

### Ruby
- **rtesseract**: Ruby wrapper for Tesseract
- Ruby Tesseract bindings

### Java
- **Tess4J**: Java JNA wrapper for Tesseract
- **OCR4J**: Java OCR library

### .NET/C#
- **Tesseract.NET**: .NET wrapper for Tesseract
- **IronOCR**: Commercial .NET OCR library
- **Syncfusion OCR**: .NET OCR processor

### PHP
- **tesseract-ocr-for-php**: PHP wrapper
- Laravel OCR packages

### Other Languages
- **Crystal**: tesseract-ocr wrapper
- **Elixir**: tesseract_ocr library
- **R**: tesseract package

## Text Detection

### Scene Text Detection
- **EAST** (Efficient and Accurate Scene Text): Fast text detection
- **CRAFT** (Character Region Awareness): Character-level text detection
- **DB** (Differentiable Binarization): Real-time text detection
- **TextSnake**: Flexible text detector

### Document Layout Analysis
- **LayoutParser**: Toolkit for document layout analysis
- **Detectron2**: Facebook's detection platform
- **DocUNet**: Document unwarping

## Preprocessing and Enhancement

### Image Processing
- **OpenCV**: Computer vision library for preprocessing
- **Pillow**: Python Imaging Library
- Image binarization techniques
- Deskewing and denoising
- Contrast enhancement

### Document Preprocessing
- Perspective correction
- Shadow removal
- Background elimination
- Resolution enhancement

## Specialized OCR Applications

### Handwriting Recognition
- **HTR (Handwritten Text Recognition)** systems
- **Transkribus**: Historical document transcription
- **Monk**: Handwriting OCR
- Cursive text recognition

### Mathematical Formula Recognition
- **LaTeX-OCR**: Convert images to LaTeX
- **Mathpix**: Mathematical OCR service
- **InftyReader**: Math document recognition

### Receipt and Invoice OCR
- Receipt scanning applications
- Invoice data extraction
- Structured data parsing
- Key-value pair extraction

### License Plate Recognition
- **OpenALPR**: Automatic license plate recognition
- **EasyALPR**: License plate detection and recognition
- Country-specific ALPR systems

### Document Understanding
- **LayoutLM**: Document understanding models
- **DocFormer**: End-to-end transformer for document understanding
- Form understanding and extraction
- Table detection and recognition

## Training and Datasets

### Datasets
- **ICDAR**: Competition datasets for text detection
- **COCO-Text**: Large-scale text detection dataset
- **SynthText**: Synthetic text dataset
- **IIIT 5K-Word**: Scene text dataset
- **Street View Text**: Google's street view dataset

### Training Tools
- Tesseract training tools
- Data augmentation for OCR
- Synthetic data generation
- Fine-tuning pretrained models

## Evaluation and Benchmarking

- Character Error Rate (CER)
- Word Error Rate (WER)
- Edit distance metrics
- Benchmark datasets
- Performance comparisons

## PDF and Document Processing

### PDF OCR Tools
- **OCRmyPDF**: Add searchable text to PDFs
- **PDFMiner**: Extract text from PDFs
- **Tabula**: Extract tables from PDFs
- **pdfplumber**: Detailed PDF analysis

### Document Conversion
- PDF to text conversion
- Image to searchable PDF
- Batch processing tools
- Cloud document APIs

## Mobile OCR

- **ML Kit**: Google's mobile OCR
- **iOS Vision Framework**: Apple's text recognition
- **Mobile Document Scanner**: Apps with OCR
- Real-time camera OCR

## Integration and Deployment

### Docker Containers
- Dockerized Tesseract
- OCR microservices
- Scalable OCR solutions

### Cloud Deployment
- AWS Lambda OCR functions
- Google Cloud Run deployments
- Azure Functions for OCR

### API Services
- REST API wrappers
- GraphQL OCR services
- Webhook integrations

## Best Practices

- Image quality optimization
- Language and script detection
- Post-processing and correction
- Confidence scoring
- Error handling strategies

## Use Cases

- Digitizing historical documents
- Automated data entry
- Accessibility (text-to-speech)
- Business card scanning
- Bank check processing
- Passport and ID verification
- Medical record digitization