# ☀️ Solar Panel Defect Detection

A computer vision project for detecting and classifying defects in solar panels using classical machine learning, deep learning, transfer learning, and object detection techniques.

## Project Overview

The project was developed in multiple phases to explore and compare different computer vision approaches for solar panel defect detection.

### Phase 1 — Classical ML & CNN

Implemented and compared image classification approaches using:

- HOG feature extraction
- SIFT with Bag of Visual Words
- SVM
- KNN
- Artificial Neural Networks (ANN)
- Convolutional Neural Networks (CNN)

Model performance was evaluated using accuracy, precision, recall, F1-score, and confusion matrices.

### Phase 2 — Transfer Learning

Applied transfer learning using a pre-trained **VGG16** model.

The convolutional layers were used for feature extraction with a custom classification head for solar panel defect classification.

### Phase 3 — Object Detection

Implemented object detection using **YOLOv8** to locate and classify solar panel defects.

Multiple YOLOv8 variants and training configurations were evaluated, including:

- YOLOv8n
- YOLOv8s
- YOLOv8m
- Data augmentation
- Hyperparameter tuning
- Multi-scale training

Models were compared using precision, recall, mAP@50, and mAP@50-95.

## Technologies

Python · TensorFlow · Keras · Scikit-learn · OpenCV · YOLOv8 · VGG16 · SVM · KNN · CNN · HOG · SIFT

## Repository Structure

```text
Assignment1_CPCS432.ipynb
    Classical ML, feature extraction, ANN, and CNN

Assignment2_Part1_CPCS432.ipynb
    VGG16 transfer learning

Assignment2_Part2_CPCS432.ipynb
    YOLOv8 object detection
```

## Key Concepts

Computer Vision · Image Classification · Object Detection · Transfer Learning · Feature Extraction · Deep Learning
