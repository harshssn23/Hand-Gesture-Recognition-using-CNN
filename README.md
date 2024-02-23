# Hand-Gesture-Recognition-using-CNN
This repository presents an implementation of a hand gesture recognition system using Convolutional Neural Networks (CNNs). The goal of this project is to accurately classify hand gestures based on input images, allowing for applications in human-computer interaction, sign language recognition, and virtual reality control.<br>
The dataset can be downloaded from kaggle using the link: https://www.kaggle.com/code/yagnes/starter-sign-language-mnist-ea42ccf3-b/input

## Overview
The hand gesture recognition system employs a deep learning architecture, specifically a Convolutional Neural Network, to effectively learn and discriminate between different hand gestures. CNNs are well-suited for image classification tasks, capturing spatial hierarchies and patterns in pixel data.

### Getting Started
Prerequisites:<br>
Python (>=3.6)<br>
TensorFlow<br>
Keras<br>
OpenCV<br>

### Usage
Run the Jupyter Notebook or Python script for hand gesture recognition

### Follow the instructions in the notebook or script to:

* Load and preprocess the hand gesture dataset.
* Design and train the CNN model.
* Evaluate the model on a test set.
* Make real-time predictions using a webcam or static images.
  
### Model Architecture
The CNN model consists of convolutional layers for feature extraction, pooling layers for spatial down-sampling, and fully connected layers for classification. Transfer learning with pre-trained models like VGG16 or ResNet can also be explored for improved performance.

### Results
The notebook includes visualizations of training curves, model architecture, and examples of correctly classified hand gestures. Evaluation metrics such as accuracy and confusion matrices provide insights into the model's performance.
