# LASSO-Regression-with-Proximal-Operator

This project implements **Lasso Regression** from scratch using both **standard gradient descent** and **proximal gradient descent**, with evaluation and visualization tools.

## 🧠 Project Overview
The goal is to compare two optimization strategies for Lasso Regression:
- **Standard Gradient Descent** (ignores L1 regularization)
- **Proximal Gradient Descent** (supports L1 regularization using soft-thresholding)

The notebook includes:
- Custom cost functions
- Support for separate bias term
- Visualizations of:
  - Loss and MSE curves
  - Predicted vs. Actual plots
  - Weight histograms

## 📊 Dataset
The notebook uses the **Concrete Compressive Strength Dataset**:
- Source: [UCI ML Repository](https://archive.ics.uci.edu/ml/datasets/concrete+compressive+strength)
- Features: Cement, Water, Superplasticizer, Age, etc.
- Target: Compressive strength (in MPa)

## 🧪 Techniques Used
- Lasso (L1) regularization
- Proximal operator (soft thresholding)
- Feature scaling (`RobustScaler`)
- Log transformation for skewed features
- Outlier handling

## 📈 Visual Outputs
- Training and Validation MSE curves
- Predicted vs Actual scatter plot
- Histograms of learned weights
- Evaluation metrics (MSE, MAE, R²)
