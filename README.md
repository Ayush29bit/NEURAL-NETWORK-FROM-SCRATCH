# NEURAL-NETWORK-FROM-SCRATCH
Implementing a neural network from scratch using NumPy , trained on the NNFS spiral dataset for multi-class classification.

This project demonstrates how to **build and train a neural network entirely from scratch** using **NumPy**, without relying on deep learning frameworks like TensorFlow or PyTorch.

The goal is to classify data points from the **spiral dataset** (generated using the `nnfs` library) into **three classes** — red, green, and blue — while understanding every step of forward propagation, backpropagation, and optimization.

---

## 🚀 Features
- Fully-connected dense layers implemented manually  
- Activation functions: ReLU and Softmax  
- Loss functions: Categorical Cross-Entropy  
- Backpropagation and gradient descent implemented from first principles  
- Visualization of the dataset, decision boundaries, and training progress  

---

## 🧩 Tech Stack
- **Python 3**
- **NumPy**
- **Matplotlib**
- **NNFS (Neural Networks from Scratch)** for dataset generation

---

## 📊 Dataset
The **spiral dataset** is a 2D toy dataset used for demonstrating multi-class classification.  
Each data point belongs to one of three intertwined spirals:
- 🔴 Class 0 (Red)  
- 🟢 Class 1 (Green)  
- 🔵 Class 2 (Blue)  

This dataset is intentionally non-linearly separable — perfect for testing a neural network’s ability to learn complex boundaries.

---

## 🧠 Learning Objectives
- Understand how forward and backward passes work mathematically  
- Implement backpropagation and gradient updates manually  
- Visualize how neural networks learn to separate non-linear data  
- Build intuition about weights, biases, activations, and loss functions  

---

## 📈 Results
After training for several epochs, the model successfully learns to separate the spiral classes, achieving **high accuracy** and smooth **decision boundaries**.

---

## 💡 Inspiration
This project is inspired by the book *[Neural Networks from Scratch (NNFS)](https://nnfs.io/)* by **Harrison Kinsley (Sentdex)** and **Daniel Kukieła**, which walks through neural network theory and implementation step-by-step.

---

## 🧰 How to Run
```bash
pip install numpy matplotlib nnfs
python your_notebook.ipynb

