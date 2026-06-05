# CNN Image Classification u

## Overview

This project implements a Convolutional Neural Network (CNN) for image classification using the CIFAR-10 dataset. The model automatically learns visual features such as edges, textures, and shapes and classifies images into one of ten predefined categories.

## Dataset

The project uses the CIFAR-10 dataset provided by TensorFlow/Keras.

Classes:

* Airplane
* Automobile
* Bird
* Cat
* Deer
* Dog
* Frog
* Horse
* Ship
* Truck

## Technologies Used

* Python
* TensorFlow
* Keras
* NumPy
* Matplotlib

## CNN Architecture

* Conv2D (32 filters, 3x3, ReLU)
* MaxPooling2D (2x2)
* Conv2D (64 filters, 3x3, ReLU)
* MaxPooling2D (2x2)
* Conv2D (64 filters, 3x3, ReLU)
* Flatten Layer
* Dense (64 neurons, ReLU)
* Dense (10 neurons, Softmax)

## Features

* Image preprocessing and normalization
* CNN-based feature extraction
* Multi-class image classification
* Accuracy and loss visualization
* Prediction on test images

## How to Run

1. Install dependencies:

pip install tensorflow numpy matplotlib

2. Run the Python file:

python cnn_for_image_classification.py

## Results

The model successfully classifies CIFAR-10 images and demonstrates the effectiveness of Convolutional Neural Networks for image recognition tasks.

## Future Enhancements

* Data augmentation
* Transfer learning using ResNet/VGG16
* Hyperparameter optimization
* Deployment using Flask or Streamlit

## Author

E. Sushanth Kumar
B.Tech CSE (Cyber Security)
Geethanjali College of Engineering and Technology
