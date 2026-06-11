# 🏠 House Price Prediction using Simple Linear Regression from Scratch

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1FkwxzrLHnKxnye2J-987_WL7RPp0QkQ8?usp=sharing)

## Overview

This project implements **Simple Linear Regression from Scratch using Gradient Descent** to predict house prices based on living area.

Instead of relying on machine learning libraries such as Scikit-Learn, the model was built manually to understand the mathematical foundations behind Linear Regression and Gradient Descent.

The project covers the complete machine learning workflow:

* Data Loading
* Data Preprocessing
* Feature Normalization
* Cost Function Implementation
* Gradient Computation
* Gradient Descent Optimization
* House Price Prediction
* Data Visualization

---

## Project Preview

### Predicted Prices vs Actual Data

![Regression Plot](images/Predicted_Prices.png)

---

## Dataset

Dataset Source:
[https://www.kaggle.com/datasets](https://www.kaggle.com/datasets/saincoder404/india-house-prices)

### Feature Used

* Living Area (Square Feet)

### Target Variable

* House Price

---

## Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Google Colab

---

## Machine Learning Concepts Implemented

### Hypothesis Function

The model predicts house prices using:

y = wx + b

where:

* x = Living Area
* w = Weight
* b = Bias
* y = Predicted House Price

### Feature Normalization

Input features and target values are standardized before training:

x_norm = (x - mean) / std

Feature normalization helps Gradient Descent converge faster and improves training stability.

---

### Cost Function

The model uses Mean Squared Error (MSE) as the cost function.

Cost = (1 / 2m) × Σ(Predicted Value − Actual Value)²

The objective of Gradient Descent is to minimize this cost.

---

### Gradient Descent

Model parameters are updated iteratively using:

w = w − α × dj_dw

b = b − α × dj_db

where:

* α = Learning Rate
* w = Weight
* b = Bias

---

## Visualizations

### Living Area vs House Price

![Living Area vs Price](images/LivingArea%20vs%20Price.png)

### Regression Line vs Actual Data

![Regression Plot](images/Predicted_Prices.png)

### Gradient Descent Convergence

![Cost Function](images/Cost%20vs%20Iterations.png)

---

## Results

The model successfully learns the relationship between living area and house price.

### Key Observations

* House price generally increases with living area.
* Living area alone cannot fully explain house prices.
* Significant variation exists in prices for houses with similar living areas.
* Additional features such as bedrooms, bathrooms, floors, and location would improve prediction accuracy.

---

## Sample Prediction

```text
Enter Size of house in Sq. Ft: 500

Predicted House Price:
88451.33682985336
```
Note: Prices are in the original dataset units.
---

## Repository Structure

```text
House-Price-Prediction-Linear-Regression/
│
├── HousePricePrediction.ipynb
├── README.md
│
└── images/
    ├── Cost vs Iterations.png
    ├── LivingArea vs Price.png
    └── Predicted_Prices.png
```

---

## What I Learned

Through this project, I gained hands-on experience with:

* Linear Regression
* Gradient Descent
* Feature Scaling
* Cost Functions
* Data Visualization
* Machine Learning Fundamentals

Most importantly, I learned how Linear Regression works behind the scenes instead of treating machine learning models as a black box.

---

## Future Improvements

* Multiple Linear Regression
* Train/Test Split
* R² Score Evaluation
* RMSE and MAE Metrics
* Feature Engineering
* Model Comparison with Scikit-Learn

---

## Run the Notebook

Open directly in Google Colab:

https://colab.research.google.com/drive/1FkwxzrLHnKxnye2J-987_WL7RPp0QkQ8?usp=sharing

---

## Author

**Prakhar Tagra**

GitHub: https://github.com/PrakharTagra

Repository: https://github.com/PrakharTagra/House-Price-Prediction-Linear-Regression
