# Aptos 2019 Blindness Detection

[![Python](https://img.shields.io/badge/python-v3.7+-blue.svg)](https://www.python.org/) 
[![TensorFlow](https://img.shields.io/badge/TensorFlow-v2.0+-orange)](https://www.tensorflow.org/) 
[![Keras](https://img.shields.io/badge/Keras-v2.3+-red)](https://keras.io/)

This project aims to develop a deep learning model for detecting diabetic retinopathy (DR) from retinal images using the Aptos dataset. The model utilizes a Convolutional Neural Network (CNN) to classify images into five categories based on the severity of diabetic retinopathy.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Model Architecture](#model-architecture)
- [Results](#results)
- [License](#license)

## Introduction

Diabetic retinopathy is a complication of diabetes that affects the eyes, leading to blindness if untreated. Early detection is crucial for managing the disease. This project focuses on building a robust CNN model to classify retinal images and assist healthcare professionals in diagnosis.

## Dataset

The dataset used in this project is the **Aptos 2019 Blindness Detection** dataset, which contains images labeled with different severity levels of diabetic retinopathy:
- **Class 0**: No DR
- **Class 1**: Mild
- **Class 2**: Moderate
- **Class 3**: Severe
- **Class 4**: Proliferative DR

The dataset includes:
- **Training samples**: 2930
- **Validation samples**: 366
- **Test samples**: 366

To address class imbalance, I have used **SMOTE (Synthetic Minority Over-sampling Technique)** to balance the dataset, resulting in improved model performance. This technique allowed me to achieve good results with a faster and lighter CNN model.

## Technologies Used

- Python
- TensorFlow/Keras
- NumPy
- Pandas
- Matplotlib
- Seaborn
- OpenCV
- imbalanced-learn (for handling class imbalance)

## Installation

To install the required packages, run the following command:

```bash
pip install -r requirements.txt
