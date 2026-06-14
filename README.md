# 🧠 Handwritten Digit Recognition Using Neural Network

## 📌 Overview
This project is a Handwritten Digit Recognition System developed using Python, TensorFlow, and Keras. The model is trained on the MNIST dataset to recognize handwritten digits from 0 to 9. It uses a simple Artificial Neural Network (ANN) to classify digit images with high accuracy.

## 🚀 Features
- Loads and preprocesses the MNIST dataset.
- Visualizes sample handwritten digit images.
- Builds and trains a Neural Network model.
- Evaluates model performance on test data.
- Generates accuracy and loss graphs.
- Predicts handwritten digits from test images.
- Saves output graphs and prediction results.

## 🛠️ Technologies Used
- Python
- TensorFlow
- Keras
- NumPy
- Matplotlib

## 📂 Dataset
The project uses the MNIST dataset:
- 60,000 training images
- 10,000 testing images
- Image size: 28 × 28 pixels
- Classes: Digits 0–9

## 🧠 Model Architecture
1. Flatten Layer (28×28 → 784)
2. Dense Layer (128 neurons, ReLU activation)
3. Dropout Layer (0.2)
4. Output Layer (10 neurons, Softmax activation)

## ▶️ How to Run
1. Install the required libraries:
```bash
pip install tensorflow numpy matplotlib
