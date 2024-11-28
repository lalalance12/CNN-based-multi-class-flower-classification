# CNN-based Multi-Class Flower Classification

## Project Overview

This project implements a multi-class Convolutional Neural Network (CNN) for classifying five different types of flowers.

## Flower Classes

- Lilly
- Lotus
- Sunflower
- Orchid
- Tulip

## Dataset Specifications

- Total Images: 5000 (1000 images per class)
- Image Preprocessing: Resized to 224x224 pixels
- Data Augmentation: Applied to improve model generalization

## Model Architecture

- Base Model: EfficientNetB0 (Transfer Learning)
- Transfer Learning Strategy:
  - Frozen base layers
  - Custom classification head
- Optimizer: Adam
- Learning Rate: 0.0001
- Loss Function: Categorical Crossentropy

## Project Structure

- `flower_classification.ipynb`: Complete CNN implementation
- `flower_classification_model.h5`: Trained model
- `training_history.png`: Training performance visualization

## Key Features

- Multi-class classification
- Image data augmentation
- Performance visualization
- Model saving and prediction function

## Prerequisites

- Python 3.8+
- TensorFlow
- Keras
- Matplotlib
- NumPy

## Usage

1. Prepare dataset in specified directory structure
2. Open Jupyter Notebook
3. Run cells sequentially
4. Use `predict_flower()` function for image classification

## Performance Metrics

- Training/Validation Accuracy tracked
- Training/Validation Loss monitored
- Model performance visualized in training history plot

## Future Improvements

- Fine-tune hyperparameters
- Experiment with different base models
- Implement learning rate scheduling
