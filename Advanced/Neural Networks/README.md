## 🧠 Neural Network on MNIST Digit Classification

### 📌 Project Overview

This project implements a **Neural Network** from scratch using popular Python libraries to classify handwritten digits from the **MNIST dataset**. The MNIST dataset is a collection of 70,000 grayscale images of handwritten digits (0 through 9), each of size 28x28 pixels.

Our goal is to train a neural network that learns to recognize these digits with high accuracy through forward propagation, backpropagation, and optimization techniques.

### 🧾 Problem Statement
Build and evaluate a multi-layer neural network to classify images of digits from the MNIST dataset.

**Input:** 28x28 grayscale image of a digit.
**Output:** Digit label (0 to 9).
**Type:** Multi-class classification problem.

### 🔍 Dataset Description

 **Source:** MNIST (Modified National Institute of Standards and Technology).
 **Training Samples:** 60,000 images
 **Test Samples:** 10,000 images
 **Image Size:** 28x28 pixels (flattened into 784 features)
 **Labels:** Digits from 0 to 9


### ⚙️ Project Workflow

1. **Data Loading:** Import and preprocess MNIST images.
2. **Normalization:** Scale pixel values between 0 and 1.
3. **Network Design:** Create a feedforward neural network with one or more hidden layers.
4. **Training:** Use forward propagation and backpropagation to adjust weights.
5. **Evaluation:** Calculate accuracy on the test dataset.
6. **Visualization:** Plot training loss and test accuracy over epochs.

---

### ✅ Outcomes

* Learned how to build and train a neural network for image classification.
* Understood how hidden layers and activation functions impact model learning.
* Visualized decision boundaries and accuracy improvements over time.
* Achieved high accuracy (> 95%) on the MNIST test set.

### 🛠️ Tools & Libraries

* Python 🐍
* NumPy
* TensorFlow / Keras or PyTorch (if used)
* Matplotlib / Seaborn for visualization
