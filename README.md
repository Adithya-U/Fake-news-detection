
# Fake News Detection - Multi-Modal Method
# Overview
This repository contains the code for a fake news detection project that uses a multi-modal method, analyzing both text and image features of an article to determine its authenticity. The model leverages BERT for text analysis and VGG16 for image analysis, combining the outputs using a dense layer with a sigmoid activation function.
# Dataset
Dataset Used: A subset of the IFND dataset.
Preprocessing: The text and image data are preprocessed separately before being fed into the respective models.
# Model Architecture
Text Analysis: BERT (Bidirectional Encoder Representations from Transformers) is used to extract features from the text data.
Image Analysis: VGG16, a convolutional neural network, is used to extract features from the image data.
Fusion Layer: The outputs from BERT and VGG16 are concatenated and passed through a dense layer with a sigmoid activation function to predict whether the news is fake or not.
Performance
# Test Accuracy: 
The model achieved a test accuracy of 84% on the subset of the IFND dataset.
