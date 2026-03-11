# MNIST Digit Classification using Deep Learning

## Project Overview
This project implements a Deep Learning model to classify handwritten digits from the MNIST dataset.  
The model is built using TensorFlow and Keras and trained on grayscale images of size 28x28 pixels.

The goal of this project is to understand the fundamentals of Neural Networks including:
- Data preprocessing
- Building dense neural network architectures
- Training models using mini-batches
- Preventing overfitting using EarlyStopping
- Evaluating classification performance

---

## Dataset
The dataset used in this project is the MNIST dataset which contains:

- 60,000 training images
- 10,000 testing images
- 10 classes (digits 0–9)

Each image has a resolution of **28 × 28 pixels**.

---

## Model Architecture

The neural network architecture used in this project:

Input Layer  
Flatten Layer (28x28 → 784 features)

Hidden Layer 1  
Dense layer with 300 neurons and ReLU activation

Hidden Layer 2  
Dense layer with 300 neurons and ReLU activation

Output Layer  
Dense layer with 10 neurons and Softmax activation

---

## Training Configuration

- Loss Function: Sparse Categorical Crossentropy
- Optimizer: Adam
- Batch Size: 32
- Epochs: 50
- Validation Split: 10%

EarlyStopping was used to prevent overfitting by monitoring validation loss.

---

## Results
The model successfully learns to classify handwritten digits with high accuracy on the validation/test dataset.

---

## Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Matplotlib
- Jupyter Notebook

---

## Project Purpose

This project was created as part of my learning journey in Deep Learning and Neural Networks.

It demonstrates how to build, train, and evaluate a neural network for image classification tasks.

---

## Author

Alaa Mohamed  
Computer Engineer | Data Science & AI Engineer
