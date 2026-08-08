# MNIST-dataset-with-pytorch

A simple deep learning project that uses PyTorch to build and train a neural network for handwritten digit classification using the MNIST dataset.

# Overview
The MNIST dataset contains 28×28 grayscale images of handwritten digits from 0 to 9. The goal of this project is to train a neural network that can recognize which digit is present in an input image.

The project covers the basic deep learning workflow:

MNIST Dataset
      ↓
Data Preprocessing
      ↓
DataLoader
      ↓
Neural Network
      ↓
Training
      ↓
Evaluation
      ↓
Prediction

# Dataset
The project uses the MNIST handwritten digit dataset.

Each image:

* Is grayscale
* Has a size of 28 × 28 pixels
* Represents one digit from 0–9

# Model
A simple fully connected neural network is used for classification.

The input images are flattened from: 28 × 28 into: 784 input features.

The network then processes these features through fully connected layers and produces predictions for the 10 possible digit classes.

# How to run the project
1. clone the repo: git clone https://github.com/Sneh-a1/MNIST-dataset-with-pytorch.git \
2. cd MNIST-dataset-with-pytorch \
3. install required packages: pip install torch torchvision numpy matplotlib \
4. Open the notebook: jupyter notebook MNIST_pytorch.ipynb 

You can also run the notebook using JupyterLab or VS Code.

# Learning Objective 
This project was created to practice the fundamentals of PyTorch and neural networks, including tensors, datasets, data loaders, model construction, training loops, loss functions, optimization, and model evaluation.

# Author 
Sneha Tamang  
GitHub: https://github.com/Sneh-a1
