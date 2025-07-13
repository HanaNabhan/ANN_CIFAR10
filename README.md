# app on ANN
A simple image classification project using an Artificial Neural Network (ANN) on the CIFAR-10 dataset.

🔍 Overview
This project demonstrates how to build and train a basic ANN for image classification using the CIFAR-10 dataset.
While CNNs are typically better suited for image tasks, this project shows what performance can be achieved with a plain feedforward ANN.

🎯 Note: Accuracy is limited due to the use of a basic ANN instead of a Convolutional Neural Network (CNN).

📦 Dataset
Name: CIFAR-10

Description: 60,000 32x32 color images in 10 classes

Source: Automatically downloaded via keras.datasets

🛠️ Model Architecture
Input Layer: 32 × 32 × 3 (flattened to 3072)

Hidden Layers: One or more dense layers with ReLU activation

Output Layer: 10 neurons with Softmax (for classification into 10 classes)

🧪 Performance
Metric	Value (Approx.)
Accuracy	~40–50%
Loss	Moderate
