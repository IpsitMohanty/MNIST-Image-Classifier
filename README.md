# MNIST-Classifier

A neural network-based image classification project using the MNIST dataset. This project demonstrates the use of Keras to build, train, and evaluate a neural network for recognizing handwritten digits.

## Project Overview
The MNIST dataset contains 60,000 training images and 10,000 test images of handwritten digits (0-9). Each image is 28x28 pixels. The objective is to classify these digits accurately using a fully connected neural network.

## Features
- Preprocessing of MNIST dataset (flattening, normalization, one-hot encoding).
- A neural network with:
  - Input layer matching the pixel dimensions.
  - Two hidden layers with ReLU activation.
  - Output layer with softmax activation for multi-class classification.
- Training with Adam optimizer and categorical crossentropy loss.
- Evaluation of accuracy on test data.

## Dependencies
The following Python libraries are required:
- `numpy`
- `keras`
- `tensorflow`
- `matplotlib`

Install the dependencies using:
```bash
pip install numpy keras tensorflow matplotlib
