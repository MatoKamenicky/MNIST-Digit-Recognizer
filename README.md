# MNIST Digit Recognizer (CNN)

This repository contains my solution for the [Kaggle Digit Recognizer competition](https://www.kaggle.com/competitions/digit-recognizer),  
using a basic Convolutional Neural Network (CNN) implemented in **PyTorch** to classify handwritten digits (0–9) from the **MNIST dataset**.

## 🚀 Overview
- **Dataset**: MNIST (28x28 grayscale images of handwritten digits)
- **Task**: Multi-class classification (digits 0–9)
- **Model**: Basic CNN with:
  - Convolutional layers
  - Max pooling
  - Fully connected layers
  - ReLU activations
  - Dropout regularization
- **Framework**: PyTorch

## 📘 Notebook
The notebook [digit-recognition-CNN](https://github.com/MatoKamenicky/MNIST-Digit-Recognizer/blob/main/digit-recognition-CNN.ipynb) contains the full solution pipeline, including:
  - Data loading
  - Exploratory Data Analysis (EDA)
  - Data preprocessing with augmentation
  - CNN model definition
  - Training loop
  - Model evaluation
  - Kaggle submission file creation

## 🧠 Model Details
The model uses three convolutional blocks with batch normalization and max pooling to extract features,  
followed by fully connected layers to classify the digits into 10 classes. The CNN model is implemented using `torch.nn.Sequential`.

## 📊 Results
- **Best accuracy**: 99.132%
- Predictions are generated in submission.csv format for direct Kaggle upload
