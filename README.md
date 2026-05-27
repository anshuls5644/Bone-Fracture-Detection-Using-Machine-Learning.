# Bone Fracture Detection using Deep Learning and Explainable AI

## Overview
This project presents a deep learning-based system for automated bone fracture detection and classification from X-ray images using advanced CNN architectures such as ResNet50, DenseNet121, EfficientNet, and VGG. The system integrates Explainable AI (XAI) techniques including Grad-CAM and LIME to improve transparency, reliability, and clinical trust in fracture detection.

The project also includes fracture severity estimation and treatment recommendation modules to support healthcare professionals in clinical decision-making.

---

## Features
- Bone fracture detection and classification from X-ray images
- Multiple CNN architectures:
  - ResNet50
  - DenseNet121
  - EfficientNet
  - VGG
- Explainable AI using:
  - Grad-CAM
  - LIME
- Fracture severity estimation
- Treatment recommendation support
- Image preprocessing and augmentation
- Performance evaluation and visualization

---

## Technologies Used
- Python
- TensorFlow / Keras
- OpenCV
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Grad-CAM
- LIME

---

## Project Structure

```bash
bone-fracture-detection/
│
├── dataset/
├── models/
├── notebooks/
├── outputs/
├── train.py
├── predict.py
├── xai.py
├── requirements.txt
└── README.md
