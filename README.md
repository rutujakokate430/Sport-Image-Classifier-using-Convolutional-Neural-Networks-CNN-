# Sport Image Classifier Using Convolutional Neural Networks (CNN)

This project implements a Convolutional Neural Network (CNN) to classify images of various sports. The classifier is designed to recognize and categorize different sports based on input images, making it useful for automated sports content tagging, image organization, or integration into larger sports analytics systems.

## Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [Technical Details](#technical-details)
- [Dataset](#dataset)
- [Training Process](#training-process)
- [Usage](#usage)
- [Requirements](#requirements)

## Project Overview

The **Sport Image Classifier** leverages deep learning techniques, specifically a CNN architecture, to classify sports images. The model supports multi-class classification and can be easily expanded to include more sports categories or fine-tuned for specific use cases.

## Features

- **Multi-class Classification**: Identify and categorize various sports.
- **CNN Architecture**: Utilizes convolutional layers for feature extraction from images.
- **High Accuracy**: Achieves robust performance in distinguishing different sports categories.
- **Scalable**: Easily adaptable for adding more sports categories or fine-tuning for specific applications.

## Technical Details

### Model Architecture

The CNN model consists of the following layers:

- **Convolutional Layers**: Used for feature extraction.
- **Max Pooling Layers**: Reduces spatial dimensions.
- **Fully Connected Layers**: Used for classification.
- **Softmax Activation**: Outputs probabilities for multi-class classification.

### Optimizer and Loss Function

- **Optimizer**: Adam
- **Loss Function**: Categorical Cross-Entropy

## Dataset

The model was trained on a diverse dataset of sports images, including the following categories:

- Cricket
- Wrestling
- Tennis
- Badminton
- Soccer
- Swimming
- Karate

## Training Process

The model was trained using the following parameters:

- **Optimizer**: Adam
- **Loss Function**: Categorical Cross-Entropy
- **Epochs**: [Number of epochs]
- **Batch Size**: [Batch size]

## Results

<img width="76" alt="Final Predictions" src="https://github.com/user-attachments/assets/16ab4033-9500-4cd7-be4e-d5694d7491f9" />


## Usage

To use the model, follow these steps:

1. **Clone the repository**:

   ```bash
   git clone https://github.com/yourusername/sport-image-classifier.git
   cd sport-image-classifier
