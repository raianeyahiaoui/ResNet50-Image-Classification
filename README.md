# ResNet50-Image-Classification
Image classification using ResNet50 on the UBIRIS V2 iris dataset. This project focuses on biometric recognition by training a deep learning model to classify iris images captured under visible light conditions.
# 🧠 ResNet50 Image Classification

This repository contains an implementation of an image classification model using **ResNet50** and a custom **Convolutional Neural Network (CNN)**. The project uses **TensorFlow** and **Keras** for deep learning, applied to the **UBIRIS V2 iris dataset** for biometric recognition.

## 🧬 Table of Contents
- [📖 Introduction](#📖-introduction)
- [🧰 Setup](#🧰-setup)
- [🧪 Usage](#🧪-usage)
- [📊 Results](#📊-results)
- [📄 License](#📄-license)

## 📖 Introduction

This project focuses on classifying iris images into 50 distinct classes using state-of-the-art deep learning techniques. It explores **transfer learning** with **ResNet50** and compares performance with a custom-designed **CNN**.

The dataset used is **UBIRIS V2**, a visible-wavelength iris image dataset often used in biometric and computer vision research.

🧪 Usage
To train the model using ResNet50:

bash
Copier
Modifier
python resnet50_train.py
To train using the custom CNN:

bash
Copier
Modifier
python custom_cnn_train.py
Modify paths and hyperparameters as needed in the scripts.

📊 Results
Training was conducted on the UBIRIS V2 dataset. Below are the achieved accuracies:

🔹 ResNet50: ~92% accuracy

🔹 Custom CNN: ~85% accuracy
## 🧰 Setup

**Requirements:**
- Python 3.x
- TensorFlow
- Keras
- Matplotlib
- Seaborn

Install dependencies using pip:

```bash
pip install tensorflow matplotlib seaborn
