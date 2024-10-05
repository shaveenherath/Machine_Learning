# Handwritten Digit Classification using Neural Network (MNIST Dataset)

This project demonstrates a simple neural network model implemented with Keras to classify handwritten digits from the MNIST dataset.

## Overview
The goal of this project is to classify handwritten digits (0-9) using a feedforward neural network built with TensorFlow and Keras. The model is trained on the popular MNIST dataset which contains 60,000 training samples and 10,000 testing samples of 28x28 pixel grayscale images.

## Dataset
The MNIST dataset consists of 70,000 images of handwritten digits from 0 to 9:
- 60,000 training images
- 10,000 test images

Each image is grayscale with a resolution of 28x28 pixels, and each pixel is represented by a value between 0 and 255.

## Model Architecture
The neural network is a fully connected feedforward model with the following layers:

- **Flatten Layer**: Converts the 28x28 pixel image into a 1D array of size 784.
- **Dense Layer 1**: 50 neurons, ReLU activation function.
- **Dense Layer 2**: 50 neurons, ReLU activation function.
- **Output Layer**: 10 neurons, Sigmoid activation function to predict the digit class.


1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/mnist-digit-classification.git
