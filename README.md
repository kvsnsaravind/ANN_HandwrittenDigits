# ANN_HandwrittenDigits

# Handwritten Digit Classification using ANN (TensorFlow)

This project implements an Artificial Neural Network (ANN) to classify handwritten digits from the [MNIST dataset](https://en.wikipedia.org/wiki/MNIST_database) using TensorFlow and Keras.

## 🧠 Project Overview

- 📚 **Dataset**: MNIST — 60,000 training and 10,000 testing grayscale images of handwritten digits (0–9).
- 🏗 **Model**: Fully connected feed-forward neural network (ANN).
- 🧪 **Framework**: TensorFlow 2.x (with Keras API).
- 🎯 **Goal**: Achieve high accuracy in classifying handwritten digits.

## 🚀 Getting Started

### Prerequisites

Make sure you have Python 3.7+ installed. Then, install the required dependencies:

**🧱 Model Architecture**
Input Layer: 784 neurons (28x28 pixels flattened)

Hidden Layer 1: 128 neurons, ReLU activation

Hidden Layer 2: 64 neurons, ReLU activation

Output Layer: 10 neurons, Softmax activation

You can customize the number of layers and neurons in the python file.

**📊 Evaluation**
The model is evaluated on the test dataset with accuracy as the primary metric. Example output:

Test accuracy: 98.2%

 **🖼 Sample Output**
After training, the script optionally shows sample predictions using matplotlib.
