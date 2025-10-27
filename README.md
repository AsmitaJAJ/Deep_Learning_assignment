# MNIST Handwritten Digit Classification using CNN

## Problem Statement
The objective of this project is to build a Convolutional Neural Network (CNN) to classify handwritten digits (0–9) from the MNIST dataset.

## Dataset
- **Source:** MNIST dataset (available via TensorFlow/Keras)
- **Size:** 70,000 grayscale images (28x28 pixels)

## 🏗️ Model Architecture
- Conv2D(32 filters, 3×3)
- MaxPooling2D(2×2)
- Conv2D(64 filters, 3×3)
- MaxPooling2D(2×2)
- Flatten
- Dense(64, ReLU)
- Dropout(0.5)
- Dense(10, Softmax)

## How to Run
```bash
python mnist_cnn.py
