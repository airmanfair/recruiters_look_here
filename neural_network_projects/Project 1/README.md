# Assignment 1 Description
In this assignment you will practice writing backpropagation code, and training Neural Networks and Convolutional Neural Networks. The goals of this assignment are as follows:

- Understand Neural Networks and how they are arranged in layered architectures
- Understand and be able to implement (vectorized) backpropagation
- Implement various update rules used to optimize Neural Networks
- Implement batch normalization for training deep networks
- Implement dropout to regularize networks
- Effectively cross-validate and find the best hyperparameters for Neural Network architecture
- Understand the architecture of Convolutional Neural Networks and gain experience with training these models on data

## Q1: Fully-connected Neural Network (30 points)
The IPython notebook FullyConnectedNets.ipynb will introduce you to our modular layer design, and then use those layers to implement fully-connected networks of arbitrary depth. To optimize these models you will implement several popular update rules.

## Q2: Batch Normalization (30 points)
In the IPython notebook BatchNormalization.ipynb you will implement batch normalization, and use it to train deep fully-connected networks.

## Q3: Dropout (10 points)
The IPython notebook Dropout.ipynb will help you implement Dropout and explore its effects on model generalization.

## Q4: ConvNet on CIFAR-10 (30 points)
In the IPython Notebook ConvolutionalNetworks.ipynb you will implement several new layers that are commonly used in convolutional networks. You will train a (shallow) convolutional network on CIFAR-10, and it will then be up to you to train the best network that you can.

## Q5: Do something extra! (up to +10 points)
In the process of training your network, you should feel free to implement anything that you want to get better performance. You can modify the solver, implement additional layers, use different types of regularization, use an ensemble of models, or anything else that comes to mind. If you implement these or other ideas not covered in the assignment then you will be awarded some bonus points.