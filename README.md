# Deep-fake-image-detection

# 🕵️ Deep Fake Image Detection using CNN (VGG16)

This project focuses on detecting **Deep Fake images** (real vs. fake) using a **Convolutional Neural Network (CNN)** built on top of the pre-trained **VGG16** model.  
It uses **transfer learning, data augmentation, and evaluation metrics** to classify images as **Real** or **Fake** with high accuracy.

---

## 📌 Features
- Transfer Learning with **VGG16 (ImageNet weights)**
- Data augmentation (rotation, zoom, flips, brightness, shear)
- Custom classification layers (Dense + Dropout for regularization)
- Binary classification: **Real** vs **Fake**
- Model evaluation using:
  - Accuracy (Train, Validation, Test sets)
  - Confusion Matrix
  - Classification Report (Precision, Recall, F1-score)
- Saves best model checkpoint (`best_model.keras`)
- Supports **Google Colab + Google Drive dataset mounting**

---

## 📂 Dataset
The dataset must be organized as follows:

Fake image detection dataset/
│── train/
│ ├── real/
│ ├── fake/
│── validation/
│ ├── real/
│ ├── fake/
│── test/
├── real/
├── fake/
Each folder contains respective **Real** and **Fake** images.  
(Default image size = `128x128`)

---
📊 Model Evaluation

Confusion Matrix (overall dataset)

Classification Report (precision, recall, F1-score)

Accuracy across Train, Validation, and Test sets
🛠 Technologies Used

Python

TensorFlow / Keras

NumPy

Matplotlib & Seaborn

Scikit-learn
