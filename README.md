# Fashion-MNIST Image Classification Using CNN

## 📌 Project Overview

This project implements a Convolutional Neural Network (CNN) to classify Fashion-MNIST images into 10 different clothing categories.

The model learns visual features from 28×28 grayscale images and predicts the category of each clothing item.

## 🎯 Objective

The main objective of this project is to build and evaluate a CNN-based image classification model using the Fashion-MNIST dataset.

## 📊 Dataset

The Fashion-MNIST dataset contains:

- 60,000 training images
- 10,000 testing images
- Image size: 28 × 28 pixels
- Grayscale images
- 10 different classes

### Classes

1. T-shirt/top
2. Trouser
3. Pullover
4. Dress
5. Coat
6. Sandal
7. Shirt
8. Sneaker
9. Bag
10. Ankle boot

## 🧠 Model Architecture

The CNN model includes:

- Convolutional Layers
- Batch Normalization
- ReLU Activation
- Max Pooling
- Dropout
- Flatten Layer
- Dense Layer
- Softmax Output Layer

## 🔄 Project Workflow

```text
Dataset
   ↓
Data Loading
   ↓
Data Preprocessing
   ↓
Pixel Normalization
   ↓
Image Reshaping
   ↓
CNN Model
   ↓
Model Training
   ↓
Model Evaluation
   ↓
Predictions
   ↓
Confusion Matrix
   ↓
Classification Report
