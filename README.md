# Neural Network From Scratch

## Overview
This project served as my introduction into machine learning with a simple 2-layer neural network with NumPy and pandas, utilizing forward and back propagation, gradient descent, and softmax. Using the classic MNIST dataset the network obtained consistent ~92% accuracy over multiple trials on randomized dev data

![Accuracy plot](accuracy_plot.png)

## How to run
```
pip install numpy pandas matplotlib
python3 main.py
```
place train.csv (I used the public MNIST set from Kaggle, super basic and popular dataset) in data/

## Structure
784 input pixels fed through 2 10-node layers
For more details on the math behind the network see Samson Zhang's "Building a neural network FROM SCRATCH (no Tensorflow/Pytorch, just numpy & math)"
