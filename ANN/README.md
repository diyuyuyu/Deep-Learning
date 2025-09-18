# 🧠 Artificial Neural Networks (ANN) - From Basics to Advanced

This repository is a **step-by-step guide** to understanding and implementing **Artificial Neural Networks (ANNs)**.  
It covers fundamental building blocks like **perceptrons** and goes deeper into **training techniques** that make networks powerful and reliable.  

---

## 📂 Topics Covered

### 🔹 1. Main Idea of ANN
- ANN is inspired by the human brain, where **neurons (nodes)** are connected to process information.
- Each neuron takes inputs, applies **weights**, passes through an **activation function**, and produces an output.
- ANNs learn patterns from data by adjusting weights using **optimization algorithms**.

---

### 🔹 2. Perceptron
#### 🟢 Single-Layer Perceptron
- Simplest form of ANN.  
- Consists of only **input layer** and **output layer**.  
- Good for solving **linearly separable problems** (e.g., AND, OR gates).  

#### 🔵 Multi-Layer Perceptron (MLP)
- Adds **hidden layers** to learn complex patterns.  
- Can solve **non-linear problems**.  
- Forms the basis of most deep learning models.  

---

### 🔹 3. Regularization
- Technique to **reduce overfitting** and improve generalization.  
- Types:  
  - **L1 Regularization (Lasso)** → Shrinks weights, promotes sparsity.  
  - **L2 Regularization (Ridge)** → Penalizes large weights, keeps them small.  

---

### 🔹 4. Activation Functions
- Introduce **non-linearity** so the network can learn complex relationships.  
- Common types:  
  - **Sigmoid** → Outputs values between 0 and 1.  
  - **Tanh** → Outputs values between -1 and 1.  
  - **ReLU (Rectified Linear Unit)** → Most popular, fast, avoids vanishing gradient.  
  - **Leaky ReLU** → Fixes the "dead neuron" problem in ReLU.  
  - **Softmax** → Converts outputs into probabilities (used in classification).  

---

### 🔹 5. Optimization Functions
- Decide **how weights are updated** to reduce loss.  
- Common algorithms:  
  - **Gradient Descent (GD)** → Updates weights step by step.  
  - **Stochastic Gradient Descent (SGD)** → Updates after each sample, faster but noisy.  
  - **Adam** → Combines momentum + adaptive learning rate (most widely used).  
  - **RMSProp** → Works well with recurrent networks.  

---

### 🔹 6. Early Stopping
- Prevents overfitting by **stopping training** when the validation loss stops improving.  
- Saves computation time and avoids unnecessary epochs.  

---

### 🔹 7. Batch Normalization
- Normalizes inputs of each layer to **stabilize training**.  
- Helps the model **train faster** and reduces sensitivity to weight initialization.  

---

### 🔹 8. Dropout
- A **regularization technique** where random neurons are "dropped" during training.  
- Prevents the network from relying too much on specific neurons.  
- Makes the model more **robust and generalizable**.  

---

## 🚀 Goal of This Repository
By the end of this repository, you will:
- Understand how **ANNs work** from the ground up.  
- Be able to **implement perceptrons and MLPs**.  
- Learn essential techniques like **regularization, dropout, and batch normalization**.  
- Master training tricks like **activation functions, optimizers, and early stopping**.  

---

## 🛠️ Requirements
- Python 3.x  
- Jupyter Notebook / Google Colab  
- Libraries:  
  ```bash
  pip install numpy pandas matplotlib scikit-learn tensorflow keras
