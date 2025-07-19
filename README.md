# 🏠 House Price Prediction Using Machine Learning (From Scratch)

This repository contains an end-to-end implementation of a **House Price Prediction** model using **Machine Learning from scratch** (without using scikit-learn for core logic). The goal is to accurately predict house prices based on features like area, bedrooms, bathrooms, and location.

---

## 📌 Project Overview

- Implemented **Linear Regression** from scratch using **Gradient Descent**
- Preprocessing includes feature normalization and handling missing data
- Evaluated using **Mean Squared Error (MSE)**
- Visualized loss convergence and model predictions
- Built for educational purposes to understand how ML works under the hood

---

## 🧠 Key Features

- ✅ Custom implementation of Linear Regression
- ✅ Gradient Descent optimization (manual calculation)
- ✅ MSE (Mean Squared Error) cost function
- ✅ Feature scaling (Z-score normalization)
- ✅ Modular and clean Python codebase
- ✅ Data visualization using Matplotlib
---

## 📁 Folder Structure

House-Price-Prediction/
│
├── data/
│ └── housing.csv # Raw dataset
│
├── src/
│ ├── linear_regression.py # Core ML logic
│ ├── utils.py # Helper functions (e.g., normalization)
│ └── train.py # Training script
│
├── notebooks/
│ └── exploratory_analysis.ipynb # EDA and visualization
│
├── results/
│ └── predictions.csv # Output predictions
│
├── requirements.txt # Python dependencies
└── README.md # Project documentation

---

## 📊 Dataset

- **Features**:
  - Area (in square feet)
  - Number of Bedrooms
  - Number of Bathrooms
  - Location
- **Target Variable**:
  - Price (in ₹)
- **Source**: *(Replace this with a real link or mention "Manually created CSV" if it's your own)*

> 📌 Tip: Ensure the dataset is placed in the `data/` directory as `housing.csv`.
