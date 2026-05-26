# UNDERWATER IMAGE CLASSIFICATION USING DEEP LEARNING MODELS

## Overview

This project presents a deep learning–based underwater image classification system developed for accurate marine species recognition using transfer learning techniques. Multiple pre-trained convolutional neural network (CNN) architectures were implemented and compared to classify underwater sea animal images captured under challenging underwater conditions such as blur, low visibility, lighting variations, and color distortion.

The project evaluates and compares the performance of different deep learning models for underwater image classification using TensorFlow and Keras frameworks.

---

# Implemented Models

* MobileNetV2
* DenseNet121
* Xception
* ResNet50V2
* NASNetMobile

---

# Dataset

The underwater image dataset contains multiple classes of marine species such as:

* Clams
* Corals
* Crabs
* Dolphin
* Eel
* Fish
* Jelly Fish
* Lobster
* Octopus
* Penguin
* Sharks
* Whale
* Turtle/Tortoise
* Sea Rays
* Starfish
* and more.

The dataset includes underwater images captured under varying environmental conditions to improve model robustness and generalization capability.

---

# Features

* Multi-class underwater image classification
* Transfer learning with pre-trained CNN models
* TensorFlow dataset pipeline optimization
* Data augmentation techniques
* Fine-tuning of deep learning models
* Comparative model analysis
* Prediction visualization
* Confusion matrix generation
* Classification report evaluation
* Performance comparison graphs

---

# Technologies Used

* Python
* TensorFlow
* Keras
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn

---

# Deep Learning Pipeline

1. Dataset Collection
2. Data Preprocessing
3. Image Resizing and Normalization
4. Label Encoding
5. Data Augmentation
6. TensorFlow Dataset Pipeline
7. Transfer Learning Model Implementation
8. Model Training and Fine-Tuning
9. Performance Evaluation
10. Prediction Visualization
11. Comparative Analysis

---

# Evaluation Metrics

The models were evaluated using:

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix
* Classification Report

---

# Model Performance Summary

| Model        | Accuracy | Precision | Recall | F1-Score |
| ------------ | -------- | --------- | ------ | -------- |
| MobileNetV2  | 81%      | 82%       | 81%    | 81%      |
| DenseNet121  | 82%      | 82%       | 82%    | 82%      |
| Xception     | 85%      | 85%       | 85%    | 85%      |
| ResNet50V2   | 83%      | 83%       | 83%    | 83%      |
| NASNetMobile | 81%      | 81%       | 81%    | 81%      |

---

# Best Performing Model

The Xception model achieved the best overall classification performance due to its superior underwater texture learning and marine feature extraction capability.

---

# Project Outputs

* Trained Deep Learning Models
* Accuracy and Loss Graphs
* Confusion Matrices
* Prediction Visualizations
* Comparative Performance Graphs
* Classification Reports

---

# Installation

## Clone Repository

```bash
git clone <your-github-repository-link>
```

## Install Dependencies

```bash
pip install -r requirements.txt
```

---

# Run Project

```bash
jupyter notebook
```

or

```bash
python main.py
```

---

# Future Enhancements

* Real-time underwater species detection
* Video-based marine classification
* Attention-based architectures
* Ensemble deep learning models
* Streamlit web deployment
* Underwater image enhancement integration

---

# Conclusion

This project demonstrates the effectiveness of transfer learning and deep learning architectures for underwater marine species classification. Comparative analysis of multiple CNN models showed that advanced architectures such as Xception and ResNet50V2 provide strong underwater classification capability with improved feature extraction and generalization performance.
