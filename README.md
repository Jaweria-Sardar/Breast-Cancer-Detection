# Classification of Breast Cancer Analysis using CNN Architectures

This repository contains a deep learning pipeline for binary classification of breast cancer (BC) using mammography images. The models utilize transfer learning with pre-trained EfficientNet architectures (B0 to B4) for high-accuracy, efficient diagnosis.

## 📌 Abstract

Early detection of breast cancer is essential for improving survival rates. This project leverages deep learning (DL) techniques to automatically classify mammogram images into benign (negative) or malignant (positive) categories. We employed EfficientNet models (B0 to B4), pre-trained on ImageNet, and fine-tuned them with custom fully connected layers for the classification task.

Key features include:

- Transfer Learning with EfficientNet (B0–B4)
- Data Augmentation for improved generalization
- Performance Evaluation using Confusion Matrix, ROC Curve, Accuracy, Precision, Recall, F1-score, and AUC
- Visualization of Model Decision Making

The best performing model, EfficientNet-B4, achieved:

- **Accuracy**: 99.53%
- **Precision**: 98.45%
- **Recall**: 99.50%
- **F1-Score**: 98.95%
- **AUC**: 0.9915

---

## 🧠 Models Used

- [x] EfficientNet-B0
- [x] EfficientNet-B1
- [x] EfficientNet-B2
- [x] EfficientNet-B3
- [x] EfficientNet-B4

Each model was fine-tuned on a binary classification dataset with medical mammography images.

---

## 🛠️ Features

- PyTorch + `timm` library for model architecture
- Optimized training loop with early stopping and learning rate scheduling
- Image preprocessing and augmentation
- Metrics tracking and visualization
- Evaluation on unseen test set



