# CIFAR-10 Image Classification with CNN

This project demonstrates how to implement Convolutional Neural Networks (CNN) on the CIFAR-10 dataset using TensorFlow and Keras. Initially, an Artificial Neural Network (ANN) was used to evaluate the score, followed by the implementation of a more advanced CNN to improve performance.

## Project Overview

The CIFAR-10 dataset consists of 60,000 32x32 color images in 10 classes, with 6,000 images per class. The dataset is divided into 50,000 training images and 10,000 testing images.

## Steps Involved

1. **Importing Libraries**: Import necessary libraries including TensorFlow and Keras.
2. **Loading the Dataset**: Download and preprocess the CIFAR-10 dataset using Keras.
3. **Implementing ANN**: Evaluate the performance of a basic ANN on the dataset.
4. **Building the CNN**:
   - Adding Convolutional Layers with ReLU activation
   - Adding Pooling Layers to reduce image complexity
   - Repeating the above steps to build a deeper network
   - Flattening the image using the Flatten layer
   - Adding Dense layers for final classification

## Requirements

To run this project, you need the following libraries:
- Python 3.x
- TensorFlow
- Keras
- NumPy

Install the required libraries using pip:

```bash
pip install tensorflow keras numpy
