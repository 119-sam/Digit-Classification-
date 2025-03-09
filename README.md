
##📌 Project Overview
This project implements a Neural Network-based digit classifier using the MNIST dataset. The model is designed to recognize handwritten digits (0-9) with high accuracy using deep learning techniques.

By leveraging data preprocessing, optimized activation functions, and a well-structured neural network, this model achieves 97% accuracy, making it an efficient solution for digit recognition tasks.



##Dataset Details
The dataset used is MNIST, which consists of grayscale handwritten digits. It is a standard benchmark dataset for image classification tasks in deep learning.

Training Samples: 60,000
Test Samples: 10,000
Image Size: 28x28 pixels
Number of Classes: 10 (digits 0-9)
Dataset Source: Keras MNIST Dataset

##Data Preprocessing
Before training the neural network, the following preprocessing steps were applied:

✔ Normalization: Pixel values are scaled to the range [0,1] to improve convergence speed and performance.

✔ Reshaping: The dataset is reshaped into flat vectors to fit the input layer of the neural network.

✔ One-Hot Encoding (Manhattan Coding): Class labels (0-9) are transformed into categorical vectors for multi-class classification.

 
 
 ##Model Architecture
The Neural Network consists of multiple layers optimized for digit classification.

Input Layer: 100 neurons to process the flattened 28x28 image vectors
Hidden Layers: 10 fully connected layers, each with 100 neurons
Activation Functions:
ReLU (Rectified Linear Unit) for hidden layers to introduce non-linearity
Sigmoid for the output layer to predict probabilities for each class
Loss Function: Categorical Cross-Entropy, used for multi-class classification
Optimizer: Adam, known for its adaptive learning rate and efficiency in deep learning
 
 
 
 ##Model Performance
The trained model achieves:

Accuracy: 97% on the test dataset
Loss Function Optimization: Converges effectively using Categorical Cross-Entropy
The high accuracy demonstrates the efficiency of deep learning-based approaches for digit classification.

