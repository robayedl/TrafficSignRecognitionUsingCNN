# TrafficSignRecognitionUsingCNN

🔎 Traffic Sign Recognition using CNN | BTSC Dataset

This project implements a Convolutional Neural Network (CNN) for traffic sign recognition using the Belgium Traffic Sign Classification (BTSC) dataset. The goal is to enhance driver assistance systems by accurately identifying traffic signs under diverse real-world conditions such as occlusion, poor lighting, and motion blur.

🚀 Features
	•	Achieved 98.45% test accuracy using an optimized CNN model.
	•	Used data augmentation (rotation, zoom, pan, brightness change) to expand the training dataset from 4575 to 22,875 images.
	•	Designed a 4-layer CNN architecture with dropout regularization and ReLU activations for robust feature extraction.
	•	Applied grayscale conversion and one-hot encoding for improved preprocessing and model compatibility.
	•	Tested with real-life car view images, achieving near-perfect recognition in practical scenarios.

🧠 Model Architecture
	•	Convolutional Layers: 4 layers with decreasing neurons (64 → 24), using kernel sizes 5 and 3.
	•	Dropout Layers: Added after convolution and dense layers for regularization.
	•	Classification Stage: 1 Dense (75 neurons) + Output (62 neurons, softmax).
	•	Training Parameters: 100 epochs, batch size 50, learning rate 0.001, Adam optimizer.

📂 Dataset
	•	Original Dataset: 7095 images, 62 traffic sign classes (BTSC).
	•	Augmented Dataset: 22,875 training images with class balancing.
	•	Preprocessing: Resized to 32×32, grayscale conversion, reshaped for CNN compatibility.

📈 Results
	•	Training Accuracy: 98.39%
	•	Testing Accuracy: 98.45%
	•	Comparison: Outperforms or matches several state-of-the-art methods in recent publications.

📌 Applications
	•	Advanced Driver-Assistance Systems (ADAS)
	•	Autonomous Vehicle Navigation
	•	Real-time Traffic Sign Detection

🔧 Future Work
	•	Experimenting with different optimizers and loss functions
	•	Implementing batch normalization
	•	Using grid search for hyperparameter tuning
