# Deepfake Detection

![Deepfake Detection](https://github.com/Preritmujoo/Deepfake-Detection/assets/95234935/970efa49-90d9-4230-b526-8d2f7932a75a)

## Introduction
This project focuses on detecting deepfake videos using deep learning techniques. The detection model leverages MTCNN for face detection, ResNext for feature extraction, and other deep learning tools like PyTorch and Gradio for building and deploying the model.

## Features
- **Face Detection:** Utilizes MTCNN architecture for accurate face detection.
- **Feature Extraction:** Employs ResNext architecture for robust feature extraction.
- **Model Training:** Built using PyTorch and torch.nn.functional for deep learning model training.
- **Web Interface:** Gradio integration for creating an interactive web-based interface for testing the model.

## Installation
To run this project, you need to have the following dependencies installed:

bash
pip install torch torchvision mtcnn gradio

## Model Architecture
### MTCNN
- Multi-task Cascaded Convolutional Networks (MTCNN) for face detection.
  
### ResNext
- ResNeXt architecture for feature extraction, known for its strong performance in image recognition tasks.

### Additional Tools
- **PyTorch:** For building and training the deep learning model.
- **torch.nn.functional:** For various neural network functions.
- **Gradio:** For creating the interactive web interface.

## Results
Include some results or metrics to demonstrate the performance of your model. This can include accuracy, precision, recall, F1-score, etc.

| Metric        | Value   |
|---------------|---------|
| Accuracy      |60% - 70% |
