# TrafficSignRecognitionUsingCNN

# 🚦 Traffic Sign Recognition using CNN

This project implements a Convolutional Neural Network (CNN) for classifying traffic signs from the Belgium Traffic Sign Classification (BTSC) dataset. The model is trained on grayscale, augmented images and achieves high accuracy in real-world scenarios.

## 🧠 Model Overview

- 4 Convolutional layers with ReLU activation
- Dropout for regularization
- 1 Dense layer (75 neurons) + Output layer (62 classes, softmax)
- Trained for 100 epochs with Adam optimizer (lr = 0.001, batch size = 50)

## 📦 Files Included

- `CNN_Grayscale.ipynb` – Model training and evaluation code
- `model.h5` – Trained CNN model weights

## 🚀 How to Use

1. Clone the repository.
2. Open `CNN_Grayscale.ipynb` in Jupyter or Google Colab.
3. Run the notebook to see model architecture, training process, and evaluation.
4. Load `model.h5` for inference.

## 🏆 Accuracy

- **Training Accuracy:** 98.39%
- **Testing Accuracy:** 98.45%

## 📚 Dataset

- **Source:** Belgium Traffic Sign Classification (BTSC)
- **Preprocessing:** Grayscale conversion, resized to 32x32, and data augmentation

## 🛠 Requirements

Install dependencies with:

```bash
pip install -r requirements.txt
