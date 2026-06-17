# Deep Learning Colon Cancer Detection

## Overview

This project develops a Convolutional Neural Network (CNN) for automated colon cancer cell classification using histopathology images. The objective is to leverage deep learning techniques to identify cancerous cells from microscopic medical images and support computer-aided diagnosis.

The system performs image preprocessing, data augmentation, model training, evaluation, and visualization for cancer cell classification.

## Dataset

The project utilizes colon histopathology image data containing microscopic cell images for cancer classification. The dataset consists of labeled histopathology images used to train and evaluate the CNN model for automated cancer detection.

## Methodology

### Data Preprocessing

* Image loading and resizing
* Data normalization
* Label encoding
* Train-test splitting

### Data Augmentation

Data augmentation techniques were applied to improve model robustness and reduce overfitting.

### CNN Model Development

The model was built using:

* Convolutional Layers (Conv2D)
* Max Pooling Layers
* Batch Normalization
* Dropout Layers
* Fully Connected Dense Layers

### Model Training

The model was trained using:

* Adam Optimizer
* Early Stopping
* L2 Regularization

### Model Evaluation

Performance was evaluated using:

* Accuracy
* Precision
* Recall
* F1-Score
* Classification Report
* Confusion Matrix

## Results

The CNN model was successfully trained and evaluated on colon histopathology image data. The project demonstrates the application of deep learning techniques for automated cancer detection and medical image analysis.

## Author

**Varadraj Tarapure**

Master of Artificial Intelligence

RMIT University
