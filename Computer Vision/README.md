# 🛒 Good Seed Supermarket: Age Verification with Computer Vision

Good Seed is a supermarket chain that wants to comply strictly with alcohol sales laws by ensuring alcohol is not sold to underage customers. As part of their initiative, this project evaluates whether computer vision can help automatically verify customer ages at checkout.

By using photographs taken at the checkout area (triggered when someone buys alcohol), the goal is to predict whether customers meet the legal age requirement, reducing the risk of underage sales.

---

## 📌 Project Objective

> **Goal**: Build and evaluate a machine learning model that can estimate a person’s age from a photograph.  
> Enable supermarkets to automatically verify customer age for alcohol purchases using checkout cameras.

---

## 🗂️ Dataset Description

- Photographs of people at checkout with their actual ages labeled.
- Images serve as features; age is the target variable for regression.
- Split into training and validation/test sets.

---

## ⚙️ Methodology

- **Data Preprocessing**:
  - Image resizing and normalization.
  - Data augmentation to increase model robustness.
- **Model Building**:
  - Convolutional Neural Network (CNN) architecture using TensorFlow/Keras.
  - Configured input layers to handle images and output age predictions.
- **Training**:
  - Used augmented and normalized images to improve generalization.
  - Monitored loss (e.g., Mean Absolute Error) during training and validation.
- **Evaluation**:
  - Plotted loss curves to assess learning progress.
  - Measured final MAE to gauge prediction accuracy on test data.

---

## 📈 Results

✅ Successfully trained CNN to estimate age from images.  
✅ Achieved acceptable MAE on validation/test set.  
✅ Demonstrated feasibility of using computer vision to automate age verification in retail.

---

## 🛠️ Skills Demonstrated

- Image preprocessing and augmentation
- Convolutional Neural Network (CNN) design
- Model training and evaluation with TensorFlow/Keras
- Regression modeling for age prediction
- Data visualization in Jupyter Notebook
- Quick Link [Here](https://github.com/Jolay96/TripleTenProjects-/blob/main/Computer%20Vision/Computer%20Vision.ipynb)