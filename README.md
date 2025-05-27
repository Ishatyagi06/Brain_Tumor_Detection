# Brain Tumor Detection using Convolutional Neural Networks (CNN)

## 📌 Overview

This project implements a Convolutional Neural Network (CNN) model for detecting brain tumors from MRI scans. The model classifies images into two main categories: **Tumor** and **No Tumor**. It leverages deep learning techniques to assist in early diagnosis and improve clinical decision-making.

---

## 📂 Dataset

The dataset used consists of labeled MRI images categorized into:
- `yes`: Images with brain tumors.
- `no`: Images without brain tumors.

> Dataset Source: [Kaggle Brain Tumor MRI Dataset](https://www.kaggle.com/navoneel/brain-mri-images-for-brain-tumor-detection) *(or insert your own source)*

---

## 🧠 Model Architecture

The CNN model consists of the following layers:
- Convolutional Layers with ReLU activation
- MaxPooling Layers for downsampling
- Dropout Layers for regularization
- Fully Connected (Dense) Layers
- Output Layer with sigmoid (for binary classification)

---

## ⚙️ Requirements

- Python 3.7+
- TensorFlow / Keras
- NumPy
- Matplotlib
- OpenCV (for image processing)
- scikit-learn
