# 🏠 House Sale Price Prediction using Machine Learning

This project builds and evaluates multiple regression models to predict **house sale prices** based on various property and location features.  

---

## 📘 Project Overview

The goal of this project is to try several machine learning models on a complicated dataset to investigate performances.  

The notebook includes:
- Data preprocessing and feature engineering  
- Linear and regularized regression (Ridge and Lasso)  
- Tree-based models (Decision Tree, Random Forest)  
- Stacking Ensemble  
- Evaluation with cross-validation and test set metrics
- A simple example of neural network

---

## ⚙️ Models Trained
| Model | Description |
|--------|--------------|
| **Linear Regression** | Baseline model |
| **Ridge and Lasso Regression** | Regularized linear models (best α selected via CV) |
| **Decision Tree Regressor** | Nonlinear model to capture interactions |
| **Random Forest Regressor** | Ensemble of decision trees for improved generalization |
| **Stacking Regressor** | Combines predictions from multiple models for best performance |
| **Neural Network (TensorFlow)** | Optional deep learning model for comparison |

---

## 📊 Evaluation Metrics
Each model is evaluated using:
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² (Coefficient of Determination)
- Cross-validated R² (mean ± std) Specifically, this one is used to compare all models between each other.

---

## 🧰 Tools & Libraries
- Python 3.10+
- NumPy, Pandas
- Scikit-learn
- Matplotlib
- TensorFlow / Keras (optional)

