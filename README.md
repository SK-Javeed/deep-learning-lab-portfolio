# Deep Learning Lab Portfolio

A comprehensive collection of Deep Learning laboratory experiments developed as part of the **22AIE304 – Deep Learning Laboratory** coursework.

The repository demonstrates the implementation of fundamental neural network concepts, progressing from a single-layer perceptron to deep neural networks using Python and modern machine learning libraries.

---

## Repository Overview

This repository contains four laboratory experiments covering the core concepts of Deep Learning.

| Lab | Topic | Objective |
|------|--------|-----------|
| Lab 1 | Perceptron | Implement a Perceptron from scratch and classify the AND gate |
| Lab 2 | Multi-Layer Perceptron (MLP) | Solve the XOR problem using different activation functions |
| Lab 3 | Hyperparameter Optimization | Evaluate multiple hyperparameter combinations and determine the best-performing model |
| Lab 4 | Deep Neural Network | Build and train a Deep Neural Network for handwritten digit classification using MNIST |

---

# Repository Structure

```
Deep-Learning-Lab-Portfolio
│
├── README.md
├── requirements.txt
│
├── Lab1_Perceptron
│   ├── code
│   ├── dataset
│   └── outputs
│
├── Lab2_MLP
│   ├── code
│   ├── dataset
│   └── outputs
│
├── Lab3_Hyperparameter_Optimization
│   ├── code
│   ├── dataset
│   └── outputs
│
└── Lab4_DNN_MNIST
    ├── code
    ├── dataset
    └── outputs
```

---

# Technologies Used

- Python 3.x
- NumPy
- TensorFlow / Keras
- Scikit-learn
- Matplotlib
- Pandas

---

# Installation

Clone the repository

```bash
git clone https://github.com/yourusername/deep-learning-lab-portfolio.git
```

Navigate to the project

```bash
cd deep-learning-lab-portfolio
```

Install dependencies

```bash
pip install -r requirements.txt
```

---

# Running the Experiments

### Lab 1

```bash
python Lab1_Perceptron/code/perceptron.py
```

### Lab 2

```bash
python Lab2_MLP/code/mlp_xor.py
```

### Lab 3

```bash
python Lab3_Hyperparameter_Optimization/code/hparam_search.py
```

### Lab 4

```bash
python Lab4_DNN_MNIST/code/dnn_mnist.py
```

---

# Datasets

### Lab 1
AND Gate Truth Table

### Lab 2
XOR Gate Truth Table

### Lab 3
Synthetic Moons Dataset generated using `make_moons()` from Scikit-Learn.

### Lab 4
MNIST Handwritten Digit Dataset.

---

# Learning Outcomes

After completing these laboratory experiments, the following concepts were explored:

- Artificial Neurons
- Perceptron Learning Algorithm
- Forward and Backpropagation
- Activation Functions
- Multi-Layer Perceptrons
- Hyperparameter Optimization
- Model Evaluation
- Deep Neural Networks
- Image Classification using MNIST

---

# Results

| Experiment | Result |
|------------|--------|
| Perceptron | Successfully classified AND gate |
| MLP | Successfully learned XOR relationship |
| Hyperparameter Search | Best configuration achieved approximately **95% validation accuracy** |
| DNN | Achieved approximately **96–97% test accuracy** on MNIST |

---

# Course Information

**Course:** 22AIE304 – Deep Learning Laboratory

**Department:** Computer Science and Engineering (Artificial Intelligence)

---

# Author

**Shaik Javeed**

B.Tech Computer Science and Engineering (Artificial Intelligence)

GitHub: https://github.com/SK-Javeed

---

## License

This repository is intended for educational and academic purposes.