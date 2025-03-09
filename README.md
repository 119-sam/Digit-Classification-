# 🧠 Digit Classification using Neural Networks

## 📌 Project Overview
This project implements a **Neural Network-based digit classifier** using the **MNIST dataset**. The model is trained to recognize handwritten digits (0-9) with **high accuracy (97%)**, leveraging **deep learning techniques**.

---

## 📂 Dataset Details
The dataset used is **MNIST**, which consists of **grayscale handwritten digits** widely used in image classification.

- **Training Samples:** 60,000  
- **Test Samples:** 10,000  
- **Image Size:** 28x28 pixels  
- **Number of Classes:** 10 (digits 0-9)  
- **Dataset Source:** [Keras MNIST Dataset](https://keras.io/api/datasets/mnist/)

---

## ⚙️ Data Preprocessing
The following preprocessing steps were applied before training:

✔ **Normalization:** Pixel values scaled to **[0,1]** for better convergence.  
✔ **Reshaping:** Converted dataset into **flat vectors** for input processing.  
✔ **One-Hot Encoding (Manhattan Coding):** Class labels transformed into categorical vectors.  

---

## 🏗️ Model Architecture
The **Neural Network** consists of multiple layers optimized for digit classification.

- **Input Layer:** `100 neurons`
- **Hidden Layers:** `10 fully connected layers` (each with `100 neurons`)
- **Activation Functions:**
  - `ReLU` for hidden layers (introduces non-linearity)
  - `Sigmoid` for the output layer (predicts class probabilities)
- **Loss Function:** `Categorical Cross-Entropy`
- **Optimizer:** `Adam`

---

## 📊 Model Performance
- **Accuracy Achieved:** `97%` on the test dataset  
- **Loss Function Optimization:** Effectively minimized using **Categorical Cross-Entropy**

---

## 🚀 Installation & Usage

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/digit-classification-nn.git
cd digit-classification-nn
