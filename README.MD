# Fruit and Vegetable Image Classifier

This project is an image classification system built using TensorFlow and Keras. It uses transfer learning with the MobileNetV2 model to classify images of fruits and vegetables. The model is trained on a custom dataset and includes data augmentation, class weighting, and fine-tuning for improved performance.

## Table of Contents
- [Overview](#overview)
- [Requirements](#requirements)
- [Dataset](#dataset)
- [Setup](#setup)
- [Training](#training)
- [Evaluation](#evaluation)
- [Results](#results)
- [License](#license)

## Overview
The goal of this project is to build a deep learning model that can accurately classify images of fruits and vegetables. The model is based on MobileNetV2, a lightweight and efficient convolutional neural network, and is fine-tuned on a custom dataset. The project includes:
- Data preprocessing with image augmentation.
- Handling class imbalance using class weights.
- Transfer learning and fine-tuning.
- Training with early stopping and learning rate reduction.
- Visualization of training and validation metrics.

## Requirements
To run this project, you need the following:
- Python 3.8 or higher
- TensorFlow 2.x
- NumPy
- Matplotlib
- scikit-learn

You can install the required packages using:
```bash
pip install tensorflow numpy matplotlib scikit-learn
