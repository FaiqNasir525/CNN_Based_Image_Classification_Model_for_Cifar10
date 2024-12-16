# CIFAR-10 Image Classification with Hyperparameter Tuning

This project aims to classify images from the CIFAR-10 dataset using a Convolutional Neural Network (CNN) with hyperparameter tuning. The project utilizes Keras Tuner to optimize the model's architecture and hyperparameters, achieving improved accuracy on image classification.

## Table of Contents
- [Overview](#overview)
- [Dataset](#dataset)
- [Techniques Used](#techniques-used)
- [Results](#results)
- [Applications](#applications)
- [License](#license)

## Overview
This project focuses on:
- Loading and preprocessing the CIFAR-10 dataset.
- Building a dynamic CNN model with tunable hyperparameters.
- Utilizing Keras Tuner for hyperparameter optimization.
- Training the optimized model on the CIFAR-10 dataset.
- Evaluating the model's performance using accuracy and loss metrics.
- Visualizing the training and validation results.

## Dataset
The dataset used is the [CIFAR-10 dataset](https://www.cs.toronto.edu/~kriz/cifar.html), which consists of 60,000 32x32 color images in 10 classes, with 6,000 images per class. There are 50,000 training images and 10,000 test images.

## Techniques Used
- **Data Preprocessing**: Normalization and data augmentation.
- **Machine Learning**: Convolutional Neural Network (CNN).
- **Hyperparameter Tuning**: Keras Tuner with RandomSearch.
- **Evaluation Metrics**: Accuracy, Loss.
- **Visualization**: Matplotlib for plotting accuracy and loss curves.


## Results
The hyperparameter tuning process resulted in an optimized model with improved accuracy compared to a baseline model. To see the output, run the code.

## Applications
This project can be applied to various image classification tasks, such as:
- Object recognition.
- Image categorization.
- Scene understanding.

## License
This project is licensed under the MIT License.
