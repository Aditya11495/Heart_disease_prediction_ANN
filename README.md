****Overview****


This project predicts whether a patient has heart disease using an Artificial Neural Network (ANN).

Heart disease is one of the leading causes of death worldwide. Early detection using machine learning and deep learning techniques can assist healthcare professionals in decision-making.

This project demonstrates how ANN can be applied to structured medical data for binary classification problems.

**Dataset**

age
sex
cp
trestbps
chol
fbs
restecg
thalach
exang
oldpeak
slope
ca
thal

**Problem Type**

Supervised Learning

Binary Classification

Target Variable:

0 → No Heart Disease

1 → Heart Disease Present

**Model Architecture**

The Artificial Neural Network consists of:

Input Layer (13 Features)

Hidden Layer 1 → 32 Neurons (ReLU)

Hidden Layer 2 → 16 Neurons (ReLU)

Output Layer → 1 Neuron (Sigmoid)

**Loss Function:**

Binary Crossentropy

Optimizer:

Adam

Evaluation Metrics:

Accuracy

Confusion Matrix

**Data Preprocessing**

Train-Test Split (80-20)

Feature Scaling using StandardScaler

Validation Split during training

Scaling is important because ANN is sensitive to feature magnitude.

**Technologies Used**

Python

TensorFlow / Keras

NumPy

Pandas

Scikit-learn

Matplotlib
