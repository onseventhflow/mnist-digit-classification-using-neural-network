# MNIST Digit Classification Using Neural Network

A machine learning project that implements handwritten digit classification on the MNIST dataset using a fully connected neural network built with TensorFlow and Keras.

---

## Overview

This repository demonstrates the design, training, and evaluation of a neural network model for classifying grayscale images of handwritten digits (0–9).  
The project emphasizes clean implementation, reproducibility, and clear documentation aligned with industry GitHub standards.

---

## Problem Statement

Given a **28×28 grayscale image** of a handwritten digit, predict the correct digit class (**0–9**).

---

## Solution Approach

- Normalize image pixel values to improve numerical stability  
- Flatten image inputs for neural network processing  
- Train a fully connected neural network using backpropagation  
- Evaluate model performance on unseen test data  

---

## Model Details

- **Architecture:** Fully Connected Neural Network (Dense layers)  
- **Activation Functions:** ReLU (hidden), Softmax (output)  
- **Loss Function:** Sparse Categorical Cross-Entropy  
- **Optimizer:** Adam  

This architecture provides a strong baseline for image classification tasks and serves as a foundation for more advanced models.

---

## Technology Stack

- Python  
- TensorFlow / Keras  
- NumPy  
- Matplotlib  

---

## Dataset

- **Name:** MNIST  
- **Training samples:** 60,000  
- **Test samples:** 10,000  
- **Image resolution:** 28 × 28 (grayscale)  
- **Number of classes:** 10  

---

## Results

- The model achieves high accuracy on the MNIST test dataset  
- Predictions are visualized to validate classification performance  
- Demonstrates effective learning using a simple neural network baseline  

---

## Repository Structure

```text
mnist-digit-classification-using-neural-network/
│
├── notebooks/
│   └── mnist_digit_classification.ipynb
│
├── README.md
├── requirements.txt
└── LICENSE```

## Results

The model achieves high accuracy on the MNIST test dataset and demonstrates stable training behavior.

### Training Loss Curve
![Loss vs Epochs](assets/Loss%20Vs%20Epochs.png)

### Sample Prediction Output
![Prediction Example](assets/prediction_example.png)


