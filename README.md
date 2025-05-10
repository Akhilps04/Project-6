# CIFAR-10 Image Classification Using CNN
A Convolutional Neural Network (CNN) built with TensorFlow/Keras to classify images from the CIFAR-10 dataset into 10 categories. The model uses data augmentation, dropout, and batch normalization to improve accuracy and prevent overfitting.

# Project Overview
This project demonstrates how to build and train a CNN for image classification on the CIFAR-10 dataset. CIFAR-10 is a collection of 60,000 32x32 color images in 10 classes, such as airplanes, automobiles, and birds. The project explores common techniques to enhance model performance.

# Features
Data Augmentation: Random flips, rotations, and zooms to expand training data.
Dropout Layers: Reduces overfitting by randomly disabling neurons during training.
Batch Normalization: Stabilizes and speeds up training.
Early Stopping: Halts training when validation accuracy stops improving.

# Dataset
Name: CIFAR-10
Classes: Airplane, Automobile, Bird, Cat, Deer, Dog, Frog, Horse, Ship, Truck
Size: 50,000 training images and 10,000 testing images.
The dataset is automatically downloaded using tensorflow.keras.datasets.

# Model Architecture
The CNN consists of:

Convolutional Layers: Extract features from images.
Max-Pooling Layers: Reduce feature map dimensions.
Dropout Layers: Prevent overfitting.
Batch Normalization: Normalize layer outputs.
Dense Layers: Perform classification using softmax for multiclass output.

# Results
The model achieved a test accuracy of ~75-85% after applying data augmentation and other enhancements.
Accuracy may vary depending on training duration, hardware, and hyperparameters.

# Acknowledgments
The dataset was sourced from Kaggle.
Thanks to my mentors and colleagues for their guidance.

📄 License
This project is for academic and demonstration purposes only. Please credit the authors if reused or modified.

