# Pet Image Classification using Convolutional Neural Networks (CNN)

This repository contains a Python script for classifying pet images (cats and dogs) using Convolutional Neural Networks (CNN). The project involves building, training, and evaluating a CNN model to classify images as either cats or dogs.

## Introduction
Image classification is a fundamental task in computer vision, with applications ranging from medical diagnosis to self-driving cars. In this project, we focus on classifying pet images into two categories: cats and dogs. The CNN model learns to recognize distinctive features in images and make predictions based on these features.

## Model Architecture
- Input Layer: Convolutional layer with 32 filters and ReLU activation function.
- Pooling Layer: Max pooling layer with a pool size of (2, 2).
- Flattening Layer: Flatten the pooled feature maps into a one-dimensional vector.
- Fully Connected Layers: Dense layers with ReLU activation function.
- Output Layer: Dense layer with a single unit and sigmoid activation function.

## Dataset
The dataset used in this project contains images of cats and dogs. Each image is resized to 64x64 pixels to maintain consistency. The dataset is split into training and testing sets for model training and evaluation.
