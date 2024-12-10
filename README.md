# YOLO Object Detection Model Training in Google Colab

 Overview

This project demonstrates how to train and evaluate a YOLO (You Only Look Once) object detection model using Google Colab. The YOLOv5 model is used for object detection tasks, such as detecting PPE (Personal Protective Equipment) in images. This notebook walks through the entire process from dataset preparation to model training and evaluation.

Features

- Dataset: The notebook works with a custom dataset (PPE detection in this case).
- Model: YOLOv5 (a state-of-the-art model for real-time object detection).
- Training: Model is trained using Google Colab, utilizing GPU for faster training.
- **Evaluation**: Evaluates the model performance on a test set.
- **Saving Weights**: Saves the best model weights for future inference.
  
Prerequisites

- Google Colab: You will need a Google account and access to Google Colab to run the notebook.
- Python Libraries: Make sure the following libraries are installed:
    - `torch`
    - `opencv`
    - `ultralytics` (for YOLOv5)

 Setup

1. Clone the Repository:
   Clone this repository to your local machine using the following command:


