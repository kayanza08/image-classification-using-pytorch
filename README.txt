# CIFAR-10 CNN Classifier

This project trains a deep Convolutional Neural Network (CNN) on the CIFAR-10 dataset using PyTorch. 
The model includes **batch normalization**, **dropout**, and a **cosine annealing learning rate scheduler** 
to improve generalization and performance.

## Features
- 5 convolutional layers with increasing filters (64 → 512)
- Batch Normalization for faster and stable training
- Dropout for reducing overfitting
- CosineAnnealingLR scheduler for adaptive learning rate
- Train/test accuracy monitoring
- Visualization of sample predictions

## Requirements
- Python 3.11+
- PyTorch >= 2.1.0
- Torchvision >= 0.16.0
- Matplotlib >= 3.7.2
- NumPy >= 1.26.0

## Installation

    2. Install dependencies:
pip install -r requirements.txt
Usage
Run the main training script:
python cnn_cifar10.py

