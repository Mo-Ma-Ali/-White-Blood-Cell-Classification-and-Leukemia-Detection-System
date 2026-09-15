# White Blood Cell Classification & Leukemia Detection

A deep learning system for analyzing blood-cell microscopy images using image classification and object detection.

The project combines neural-network-based classification with YOLO-based object detection and provides an application for displaying analysis results.

## Overview

The system focuses on two related tasks:

1. White blood cell classification
2. Leukemia detection and classification

The project also includes object detection for locating cells in microscopy images.

## Workflow

```text
Blood Cell Image
       │
       ▼
Image Preprocessing
       │
       ├───────────────┐
       ▼               ▼
Cell Classification   Object Detection
       │               │
       ▼               ▼
Cell / Leukemia      Cell Locations
Classification
       │
       └───────┬───────┘
               ▼
          Results
```

## Features

* Blood-cell image preprocessing
* Grayscale image processing
* CNN-based image classification
* White blood cell classification
* Leukemia classification
* YOLO-based object detection
* Prediction visualization
* Confusion matrix and evaluation workflows
* PDF report generation
* Desktop application interface

## Leukemia Classes

The project works with the following classes:

* ALL
* AML
* CLL
* CML
* WBC

## Technologies

* Python
* PyTorch
* TensorFlow / Keras
* YOLOv8
* OpenCV
* NumPy
* Pandas
* Matplotlib

## Repository Structure

```text
├── App.py
├── blood_model.py
├── PdfGenerator.py
├── Models/
├── Models files trainner/
├── weights/
├── assets/
├── WBC_report.pdf
└── Lukiemia_report.pdf
```

## Application

The project includes an application that allows the user to perform blood-cell analysis and generate reports from the results.

The PDF generation component is used to create analysis reports.

## Model Development

The project includes separate workflows for classification and object detection.

### Classification

CNN-based models are used to classify blood-cell images into the defined categories.

### Object Detection

YOLOv8 is used to detect and locate blood cells within images.

## Evaluation

The project includes evaluation and visualization workflows for analyzing model predictions.

These include:

* Confusion matrices
* Prediction results
* Visualized detections
* Classification results

## Purpose

The project was developed as a computer vision application for studying deep learning methods in medical image analysis, particularly blood-cell classification and leukemia detection.
