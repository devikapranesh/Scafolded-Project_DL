MLP vs CNN on Fashion-MNIST Deep Learning Comparative Study

1.  Problem Statement

This project implements and compares a Multi-Layer Perceptron (MLP) and
a Convolutional Neural Network (CNN) for image classification using the
Fashion-MNIST dataset.

The objective is to: 
- Establish an MLP as a baseline model 
- Improve performance using CNN 
- Analyze feature representation differences 
- Control overfitting 
- Evaluate performance using quantitative and qualitative metrics 
- Build a reproducible deep learning workflow

2.  Dataset

Dataset: Fashion-MNIST Source:
https://github.com/zalandoresearch/fashion-mnist

Fashion-MNIST consists of:

60,000 training images
10,000 test images
28x28 grayscale images
10 clothing categories

Classes:
T-shirt/top,Trouser,Pullover,Dress,Coat,Sandal,Shirt,Sneaker,Bag,Ankle boot

All images were normalized to the range [0,1].


# Scaffolded Project 1  
## CNN vs MLP – Image Classification Comparison

---

## 📌 Project Overview

This project implements and compares two deep learning architectures:

1. Multi-Layer Perceptron (MLP)
2. Convolutional Neural Network (CNN)

The goal is to understand how CNNs improve feature learning compared to traditional fully connected neural networks when working with image data.

The notebook demonstrates model construction, training, evaluation, and performance comparison using TensorFlow and Keras.

---

## 🧠 Key Concepts Covered

- Artificial Neural Networks (ANN)
- Multi-Layer Perceptron (MLP)
- Convolutional Neural Networks (CNN)
- Feature extraction vs raw pixel learning
- Dense layers
- Conv2D layers
- Model training and evaluation
- Performance comparison

---

## 🛠 Technologies Used

- Python 3.x
- TensorFlow
- Keras
- NumPy
- Matplotlib
- Jupyter Notebook

---

## 🏗 Model Architectures

### 1️⃣ MLP Model
- Flattened image input
- Fully connected Dense layers
- Learns from raw pixel values
- Higher parameter count
- Limited spatial feature awareness

### 2️⃣ CNN Model
- Conv2D layers
- Feature maps
- Spatial pattern learning
- Better generalization for image tasks
- Improved performance compared to MLP

---

## 📊 Objective of Comparison

This project demonstrates:

- Why CNNs outperform MLPs on image classification tasks
- How convolution layers extract spatial features
- The importance of architectural choice in deep learning

---

## 🚀 How to Run

1. Install required libraries:

   pip install tensorflow keras numpy matplotlib

2. Open Jupyter Notebook:

   jupyter notebook

3. Open:
   Scaffolded_Project1_CNN_&_MLP.ipynb

4. Run all cells sequentially.

---

## 📁 File Structure

/project-folder  
│  
├── Scaffolded_Project1_CNN_&_MLP.ipynb  
├── README.txt  

---

## 📈 Expected Learning Outcomes

After completing this project, you should understand:

- The structural difference between MLP and CNN
- Why CNNs are better suited for image data
- How feature learning improves classification accuracy
- The role of convolution in deep learning

---


