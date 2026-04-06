Medium Link: https://medium.com/p/f4312523d94b?postPublishedType=initial
Fashion MNIST Classification with CNN
Overview

This project implements a Convolutional Neural Network (CNN) to classify images from the Fashion MNIST dataset. The goal is to build a model capable of accurately identifying different categories of clothing items from grayscale images.

Dataset

The Fashion MNIST dataset consists of 70,000 grayscale images of size 28x28 pixels:

60,000 training samples
10,000 test samples
10 classes
Classes
T-shirt/top
Trouser
Pullover
Dress
Coat
Sandal
Shirt
Sneaker
Bag
Ankle boot
Methodology

The workflow includes:

Data loading and preprocessing
Normalization of pixel values
Model design using convolutional and dense layers
Training and validation
Model evaluation on test data
Model Architecture

The CNN model includes:

Convolutional layers for feature extraction
Max pooling layers for dimensionality reduction
Fully connected layers for classification
ReLU activation for hidden layers
Softmax activation for output layer
Technologies
Python
TensorFlow / Keras
NumPy
Matplotlib
