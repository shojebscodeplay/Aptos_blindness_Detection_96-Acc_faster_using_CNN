# Aptos 2019 Blindness Detection

[![Python](https://img.shields.io/badge/python-v3.7+-blue.svg)](https://www.python.org/) 
[![TensorFlow](https://img.shields.io/badge/TensorFlow-v2.0+-orange)](https://www.tensorflow.org/) 
[![Keras](https://img.shields.io/badge/Keras-v2.3+-red)](https://keras.io/)

A deep learning-based approach to detect diabetic retinopathy in eye images using Convolutional Neural Networks (CNNs). This project leverages the **APTOS 2019 Blindness Detection dataset** and achieves **96% accuracy** with an optimized Faster CNN architecture.

## 📜 Project Overview

Diabetic retinopathy (DR) is a leading cause of blindness worldwide, and early detection is crucial for treatment. This project aims to classify the severity of DR using retinal images into 5 categories:

- **No DR**
- **Mild**
- **Moderate**
- **Severe**
- **Proliferative DR**

The model is trained using an efficient CNN architecture, with fine-tuned hyperparameters and image preprocessing techniques for high accuracy and faster inference.

## 📂 Project Structure


├── README.md # Project Documentation ├── train.csv # Training labels ├── test.csv # Test image IDs ├── train_images/ # Training images directory ├── test_images/ # Test images directory ├── aptos_blindness_detection.ipynb # Jupyter Notebook for model training and evaluation ├── model.py # Python script for model architecture and training └── requirements.txt # Required packages and dependencies
