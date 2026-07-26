# Deep Learning Lab

This repository contains the implementation of Deep Learning laboratory experiments completed as part of **CS3807 – Deep Learning Laboratory** at **Shiv Nadar University Chennai**. The experiments are implemented in **Python** using **Google Colab** and cover the fundamentals of neural networks, data preprocessing, model training, evaluation, and visualization.

## Experiments

### Experiment 1 – Single Layer Perceptron for Binary Classification

Implementation of a Single Layer Perceptron from scratch to perform binary classification on the **Banknote Authentication Dataset**.

**Topics Covered**
- Exploratory Data Analysis (EDA)
- Data preprocessing and feature normalization
- Perceptron learning algorithm
- Step activation function
- Model training and evaluation
- Performance metrics
- Decision boundary visualization

**Dataset**
- **Dataset:** Banknote Authentication Dataset (UCI Machine Learning Repository)
- **Instances:** 1,372
- **Features:** Variance, Skewness, Curtosis and Entropy
- **Classes:** Authentic and Forged Banknotes

**Additional Tasks**
- Perceptron implementation for AND, OR and NOT logic gates
- Weight updates after each iteration
- Decision boundary visualization after every weight update

---

### Experiment 2 – Multi-Layer Perceptron for Multi-Class Image Classification

Implementation of a Multi-Layer Perceptron (MLP) using TensorFlow/Keras for multi-class image classification.

**Topics Covered**
- Dataset exploration
- Image preprocessing
- Data normalization
- One-hot encoding
- MLP model construction
- Model training and evaluation

**Dataset**
- **Dataset:** Fashion-MNIST
- **Training Images:** 60,000
- **Testing Images:** 10,000
- **Image Size:** 28 × 28
- **Classes:** 10 fashion categories

**Additional Tasks**
- Automated hyperparameter optimization
- Comparison of baseline and optimized models using performance metrics and visualizations.
- Implementation of the Perceptron Learning Algorithm for the XOR gate.
- Analysis of the non-linearly separable nature of the XOR problem and the resulting failure of the Perceptron algorithm to converge.

---

## Repository Structure

```
Deep-Learning-Lab/
├── Experiment_1_Perceptron.ipynb
├── Experiment_2_MLP.ipynb
├── Lab 1 Plots/
├── Lab 2 Plots/
├── README.md
└── requirements.txt
```

## Technologies Used

- Python
- Google Colab
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- TensorFlow / Keras

## Getting Started

Clone the repository and install the required packages.

```bash
git clone https://github.com/<your-username>/Deep-Learning-Lab.git
cd Deep-Learning-Lab
pip install -r requirements.txt
```

The notebooks can be opened directly in **Google Colab** or executed locally using a Python environment with the listed dependencies.

---
