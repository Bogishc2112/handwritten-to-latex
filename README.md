# Handwritten-to-latex for Artificial intelligence @ UCF
Current state: *in progress, OCR model in development*
## About:
The goal of the project is to build the model which would be able to convert handwritten mathematical formula in the form of an image to a LaTeX expressions. This repository currently contains only a model for single character recognition
## Model:
The model is CNN with 9 layers(3 conv layers, 3 pooling layers, 3 fully connected layers). The accuracy of CNN tested on MNIST, EMNIST and kaggle math written symbols datasets is approximately 98, 87, 98 % consequently. The top version of the model can recognize 82 classes. The script proposing the possible model architecture based on the size of the image in the dataset was written.

Hyperparameter | Value
---|---
Learning rate | *5e-4*
Optimizer | *Adam, beta1=0.9, beta2=0.999, eps=1e-6*
Number of epochs | *20*
Batch | *64 images*
## Todo:
Current goal is to develop own symbolic dataset and to start development of OCR model which will be able to recognize single symbols on the photo to pass them to this model.
