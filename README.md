# ⚡ EV Car Prices - Regression Analysis

This repository contains the completed machine learning assignment on **electric vehicle (EV) car prices**, using preprocessed data scraped from [Bilbasen.dk](https://www.bilbasen.dk/) by previous MAL1 students. The primary focus is to apply various regression techniques and evaluate their performance on predicting car prices based on technical specifications.

## 📁 Contents

- `car_prices.xlsx`: Preprocessed dataset containing technical and pricing information on electric vehicles.
- `ev_car_price_regression.ipynb`: Jupyter Notebook with data loading, preprocessing, model training, and evaluation.
- `README.md`: Project documentation and overview.

## 🎯 Objective

The goals of this assignment were:

1. Understand how **linear algebra** underpins machine learning techniques, particularly correlation and regression.
2. Implement and compare the following regression models:
   - Multiple Linear Regression
   - Ridge Regression
   - Lasso Regression
   - Elastic Net
3. Evaluate model performance using appropriate regression metrics and cross-validation strategies.

## 🧾 Dataset Overview

The dataset contains **16 explanatory variables** and one **response variable**:

- 📌 **Response Variable**:
  - `Price (DKK)`: Listed price of the EV in Danish Kroner.

- ⚙️ **Features**:
  - `Model Year`
  - `Mileage (km)`
  - `Electric Range (km)`
  - `Battery Capacity (kWh)`
  - `Energy Consumption (Wh/km)`
  - `Annual Road Tax (DKK)`
  - `Horsepower (bhp)`
  - `0-100 km/h (s)`
  - `Top Speed (km/h)`
  - `Towing Capacity (kg)`
  - `Original Price (DKK)`
  - `Number of Doors`
  - `Rear-Wheel Drive` (binary)
  - `All-Wheel Drive (AWD)` (binary)
  - `Front-Wheel Drive` (binary)

## 📊 Workflow Summary

1. **Data Import & Splitting**
   - Imported `car_prices.xlsx`
   - Created `X` (features) and `y` (response)
   - Split into training and test sets: `X_train`, `X_test`, `y_train`, `y_test`
   - Used a fixed `random_state=42` for reproducibility

2. **Modeling Techniques**
   - Applied and tuned multiple regression models
   - Used regularization techniques to handle multicollinearity and improve generalization

3. **Evaluation**
   - Compared model performance using:
     - Mean Squared Error (MSE)
     - R² score
     - Cross-validation scores
   - Interpreted coefficients to understand variable importance

## 🧪 Tools & Libraries Used

- Python 3.x
- Jupyter Notebook
- pandas, numpy
- scikit-learn
- matplotlib, seaborn

## 🚀 Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/ev-car-price-regression.git
