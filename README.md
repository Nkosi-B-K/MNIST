# MNIST
MNIST Handwritten Digit Classification This project implements a convolutional neural network (CNN) to classify handwritten digits from the MNIST dataset using TensorFlow and Keras. 
The goal was to build a model that accurately identifies digits (0-9) from a collection of 70,000 images.

The MNIST dataset is a classic benchmark in machine learning, often used to evaluate image classification algorithms. This project focuses on data preprocessing, model design, and performance evaluation to achieve high classification accuracy.

#Technologies Used
Python
TensorFlow
Keras
NumPy
Matplotlib
Jupyter Notebook
Dataset
The dataset consists of 70,000 grayscale images of handwritten digits, divided into 60,000 training images and 10,000 testing images. The images are 28x28 pixels in size.

#Model Architecture
The model consists of:

Input Layer: Flatten layer to convert 2D images into 1D vectors.
Hidden Layers: Two dense layers with ReLU activation to learn complex features.
Output Layer: Softmax activation for multi-class classification (10 classes corresponding to digits 0-9).
Results
Achieved a test accuracy of 98.5%.
Visualized training and validation loss and accuracy using Matplotlib.
