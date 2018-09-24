# Assignment 2 Description
In this assignment you will implement recurrent networks, and apply them to image captioning on Microsoft COCO. You will also explore methods for visualizing the features of a pretrained model on ImageNet, and also this model to implement Style Transfer.

The goals of this assignment are as follows:

- Understand the architecture of recurrent neural networks (RNNs) and how they operate on sequences by sharing weights over time
- Understand and implement both Vanilla RNNs and Long-Short Term Memory (LSTM) RNNs
- Understand how to sample from an RNN language model at test-time
- Understand how to combine convolutional neural nets and recurrent nets to implement an image captioning system
- Understand how a trained convolutional network can be used to compute gradients with respect to the input image
- Implement and different applications of image gradients, including saliency maps, fooling images, class visualizations.
- Understand and implement style transfer.

## Q1: Image Captioning with Vanilla RNNs (30 points)
The Jupyter notebook RNN_Captioning.ipynb will walk you through the implementation of an image captioning system on MS-COCO using vanilla recurrent networks.

## Q2: Image Captioning with LSTMs (30 points)
The Jupyter notebook LSTM_Captioning.ipynb will walk you through the implementation of Long-Short Term Memory (LSTM) RNNs, and apply them to image captioning on MS-COCO.

## Q3: Network Visualization: Saliency maps, Class Visualization, and Fooling Images (20 points)
The Jupyter notebooks NetworkVisualization-TensorFlow.ipynb /NetworkVisualization-PyTorch.ipynb will introduce the pretrained SqueezeNet model, compute gradients with respect to images, and use them to produce saliency maps and fooling images. Please complete only one of the notebooks (TensorFlow or PyTorch). No extra credit will be awardeded if you complete both notebooks.

## Q4: Style Transfer (20 points)
In the Jupyter notebooks StyleTransfer-TensorFlow.ipynb/StyleTransfer-PyTorch.ipynb you will learn how to create images with the content of one image but the style of another. Please complete only one of the notebooks (TensorFlow or PyTorch). No extra credit will be awarded if you complete both notebooks.