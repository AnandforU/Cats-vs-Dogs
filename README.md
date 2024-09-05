# Cats vs Dogs Prediction

## Overview

This project aims to build a deep learning model to classify images of cats and dogs. It uses TensorFlow and Keras for implementing the Convolutional Neural Network (CNN) model.
The model is designed to distinguish between images of cats and dogs.

## Dataset used - https://www.kaggle.com/datasets/salad...

## Frameworks and Libraries

The following frameworks and libraries are used in this project:

- **TensorFlow**: An open-source library for numerical computation and machine learning.
- **Keras**: A high-level API for building and training deep learning models.
##Model Architecture

The model is built using the following layers:

Conv2D: Convolutional layer for feature extraction.
MaxPooling2D: Pooling layer to reduce the dimensionality of the feature maps.
Flatten: Flattening layer to convert 2D feature maps into 1D vectors.
Dense: Fully connected layer for classification.
BatchNormalization: Normalizes activations and gradients, helping to stabilize and accelerate training.

## Requirements

To run this project, you need to have the following libraries installed:

- TensorFlow 2.x

You can install the required packages using pip:

```bash
pip install tensorflow

