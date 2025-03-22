# Cloud Image Classification by CNN
## ❄️Overview

This repository contains a deep learning model for classifying cloud images using PyTorch. The model extracts features from cloud images using a convolutional neural network (CNN) and classifies them into different cloud types.

## ❄️Features

- **Dataset Handling**: Loads and processes cloud images for training and testing.
- **Data Augmentation**: Enhances dataset variability to improve model robustness.
- **Model Architecture**: Implements a convolutional neural network (CNN) to predict cloud categories.
- **Training & Evaluation**
- 
## ❄️Model Architecture
The model consists of:
- **Feature Extractor**: Uses two convolutional layers with ELU activation and max pooling.
- **Classifier**: A fully connected layer that takes the flattened feature map and outputs predictions for cloud type classification.
