# AI Project 4 – OCR Image Processing Pipeline

## Overview

This project demonstrates an Optical Character Recognition (OCR) pipeline using image preprocessing and Tesseract OCR.

The pipeline improves image quality before extracting text and highlights recognized text with confidence scores.

## Features

- Image preprocessing
- Grayscale conversion
- Gaussian blur
- Thresholding
- Deskewing
- OCR using Tesseract
- Confidence filtering
- Annotated output image

## Technologies Used

- Python 3
- OpenCV
- NumPy
- Pillow
- Pytesseract

## Project Structure

```
AI-Project4/
│── project4_ocr_pipeline.py
│── generate_sample.py
│── sample_input.png
│── output_annotated.png
│── README.md
```

## Installation

```bash
pip install opencv-python numpy pillow pytesseract
```

Install Tesseract OCR separately and ensure it is available in your system PATH.

## Run

Generate sample image:

```bash
python generate_sample.py
```

Run OCR:

```bash
python project4_ocr_pipeline.py
```

## Output

- Extracted text
- Confidence scores
- Annotated output image showing detected text regions

## Learning Outcomes

- Image preprocessing
- OCR fundamentals
- Computer Vision
- OpenCV operations
- Text recognition using Tesseract