# Diabetes Prediction Model (PyTorch)

This project builds a neural network using PyTorch to predict whether a patient has diabetes based on the Pima Indians Diabetes dataset. This work is part of the final portfolio for CSC484 – Advanced Topics in Software Development with Python.

---

## 📊 Dataset
The dataset used is the Pima Indians Diabetes dataset, containing 768 patient records with 8 medical predictor variables and a binary outcome (diabetes or not).

Source:
https://raw.githubusercontent.com/jbrownlee/Datasets/master/pima-indians-diabetes.data.csv

Features:
- preg: Number of pregnancies
- plas: Plasma glucose concentration
- pres: Blood pressure
- skin: Skin fold thickness
- insu: Insulin level
- mass: BMI
- pedi: Diabetes pedigree function
- age: Age in years

---

## 🧠 Model
A fully connected neural network built with PyTorch:

- Input layer: 8 features  
- Hidden layer 1: 16 neurons, ReLU  
- Hidden layer 2: 8 neurons, ReLU  
- Output layer: 1 neuron, Sigmoid  

Loss function: Binary Cross Entropy  
Optimizer: Adam (lr=0.001)

---

## 🚀 Training
The model is trained for 50 epochs using a batch size of 32.  
Training includes forward propagation, loss calculation, backpropagation, and weight updates.

---

## 📈 Evaluation
The model is evaluated on a 20% test split.  
Metrics:
- Accuracy score
- Sample predictions

---

## 📸 Screenshots
Screenshots included in the `/screenshots` folder:
- Dataset preview
- Model architecture
- Training output
- Evaluation results
- GitHub repository view

---

## 📂 Project Structure

