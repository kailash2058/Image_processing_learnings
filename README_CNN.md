# Convolutional Neural Network for CIFAR-10 Classification

This repository contains Python code examples for implementing a Convolutional Neural Network (CNN) using TensorFlow/Keras for classifying images from the CIFAR-10 dataset.

## Overview

In this project, we build a CNN model to classify images from the CIFAR-10 dataset. The CIFAR-10 dataset consists of 60,000 32x32 color images in 10 classes, with 6,000 images per class. The classes are: airplane, automobile, bird, cat, deer, dog, frog, horse, ship, and truck.

The steps involved in this project include:

1. Data loading and preprocessing: The CIFAR-10 dataset is loaded using Keras's `load_data` function. The data is then preprocessed by scaling the pixel values to the range [0, 1].

2. Model architecture definition: We define a CNN model architecture using the Sequential API in Keras. The model consists of convolutional layers, max pooling layers, batch normalization, and fully connected layers.

3. Model training: The model is trained using the training data (X_train) and labels (y_train) for a specified number of epochs.

4. Model evaluation: The trained model is evaluated on the test data (X_test) and labels (y_test) to measure its performance in terms of accuracy.

## Requirements

- Python 3.x
- TensorFlow 2.x
- Keras
- NumPy
- Matplotlib



