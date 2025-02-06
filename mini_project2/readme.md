# 🤖 Mini Project #2 - Fundamentals of Intelligent Systems  

This repository contains **Mini Project #2** for the **Fundamentals of Intelligent Systems** course by **Amir Mohammad Saffar**, under the supervision of **Dr. Aliyar Shorehdeli**.

## 📌 Project Overview  

This project explores various machine learning concepts, including **neural networks, activation functions, optimization algorithms, and feature engineering**. It is structured into multiple sections:

1️⃣ **Comparison of Activation Functions** 🔥  
2️⃣ **Feature Correlation Analysis** 📊  
3️⃣ **Impact of Hyperparameters in Neural Networks** 🎛️  
4️⃣ **Binary Image Conversion & Noise Handling** 🖼️  
5️⃣ **Reconstructing Missing Data using Hamming Networks** 🔄  
6️⃣ **Radial Basis Function (RBF) Neural Networks** 🌐  

---

## 🔥 Question 1: Activation Function Analysis  

This section investigates how different activation functions impact neural network performance.

### 🏆 Key Comparisons  
- **ReLU (Rectified Linear Unit)** ⚡  
  - Fast and widely used, but may suffer from **Dead Neurons** 🚫.  
- **ELU (Exponential Linear Unit)** 📈  
  - Addresses the **Dead Neurons** issue by allowing small negative outputs.  

### ✅ Findings  
- **ELU performed better than ReLU** for handling negative inputs.  
- ReLU’s **zero gradient issue** could hinder learning in deep networks.  

---

## 📊 Question 2: Feature Correlation Analysis  

This section explores the relationship between **tenure, education**, and other customer-related features.

### 🔍 Insights  
- A **heatmap analysis** showed **high correlation** between **tenure & education** 🏫.  
- Histograms were used to visualize distributions for key features 📉.  

---

## 🎛️ Question 3: Impact of Hyperparameters  

Experiments with **different hyperparameters** for optimizing neural networks.

### 🚀 Techniques Used  
- **Batch Normalization** 📏: Improved model convergence.  
- **Dropout** 🛑: Prevented overfitting, but impact was limited.  
- **L2 Regularization** 🔒: Reduced model complexity without significant accuracy change.  
- **Optimizers Tested** ⚙️:  
  - **Adam** ➝ 40.5% accuracy 📈  
  - **RMSprop** ➝ 41.9% accuracy 🚀  
  - **Ensemble Model** ➝ 37% accuracy ❌  

### 🏆 Best Model  
🔹 **RMSprop achieved the highest accuracy (41.9%)** on the validation dataset.  

---

## 🖼️ Question 4: Binary Image Conversion & Noise Handling  

This section converts images into **binary format** and **adds noise** to study its effect.  

### 📌 Methods Implemented  
- **convertImageToBinary()** 📷: Converts images to binary form (black & white).  
- **getNoisyBinaryImage()** 🔊: Adds **random noise** to test robustness.  

### ⚠️ Key Observations  
- Adding **too much noise reduced model accuracy** significantly.  
- **Interpolation & Autoencoders** could help recover missing pixels.  

---

## 🔄 Question 5: Reconstructing Missing Data using Hamming Networks  

**Hamming Networks** were used to reconstruct missing image data.

### 🧐 Observations  
- **30-50% missing pixels** ➝ Model accuracy remains stable (~50%).  
- **Above 50% missing data** ➝ Model struggles to reconstruct images ❌.  
- **Techniques like interpolation & autoencoders can enhance performance**.  

---

## 🌐 Question 6: Radial Basis Function (RBF) Neural Networks  

A **Radial Basis Function (RBF) network** was implemented for **California Housing Price Prediction** 🏠.

### 🔍 Implementation Steps  
1️⃣ **Load and preprocess the dataset** 📂.  
2️⃣ **Define an RBF layer** with Gaussian basis functions.  
3️⃣ **Compare RBF vs. Dense networks** for regression.  

### 📊 Key Results  
- **RBF performed better in capturing non-linear patterns**.  
- **Dense networks worked well for large datasets with uniform distributions**.  

---

## 🚀 Future Improvements  
🔹 **Hyperparameter Tuning** 🎛️: Use Grid Search to optimize model parameters.  
🔹 **Data Augmentation** 📈: Generate more training data to improve performance.  
🔹 **Exploring More Activation Functions** 🤖: Try Swish, SELU, and Leaky ReLU.  

---

## 📜 License  
This project is licensed under the **MIT License**.  

## 🙏 Acknowledgments  
Special thanks to **Scikit-Learn, TensorFlow, and Keras** for providing powerful tools to implement this project!  

---
