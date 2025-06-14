# 🏠 House Price Prediction using XGBoost

This project aims to predict the **price of a house** based on various features such as area, number of bedrooms, bathrooms, furnishing status, and more using the **XGBoost Regressor** — a powerful and efficient implementation of gradient boosting.

## 📌 Project Overview

Predicting house prices accurately is essential for real estate professionals, investors, and buyers. This machine learning model is trained to learn complex patterns in structured housing data and provide reliable price predictions.

## 📂 Dataset

The dataset contains various attributes of houses, including both **numerical** and **categorical** features:

| Feature | Description |
|--------|-------------|
| `price` | Target variable — price of the house (in currency units) |
| `area` | Size of the house (in square feet) |
| `bedrooms` | Number of bedrooms |
| `bathrooms` | Number of bathrooms |
| `stories` | Number of floors/stories |
| `parking` | Parking space available (0–n cars) |
| `mainroad_yes` | Is the house on the main road? (1 = Yes, 0 = No) |
| `guestroom_yes` | Is there a guest room? (1 = Yes, 0 = No) |
| `basement_yes` | Is there a basement? (1 = Yes, 0 = No) |
| `hotwaterheating_yes` | Is hot water heating available? (1 = Yes, 0 = No) |
| `airconditioning_yes` | Is air conditioning available? (1 = Yes, 0 = No) |
| `prefarea_yes` | Is the house in a preferred area? (1 = Yes, 0 = No) |
| `furnishingstatus_semi-furnished` | Furnishing status (1 if semi-furnished) |
| `furnishingstatus_unfurnished` | Furnishing status (1 if unfurnished) |

> Note: Categorical features have already been encoded into binary (1/0) format.

## ⚙️ Tech Stack

- Python
- NumPy, Pandas
- Scikit-Learn
- Matplotlib, Seaborn
- **XGBoost**

## 🚀 Model Used

- **XGBoost Regressor**
  - Handles both linear and non-linear relationships
  - Efficient, scalable, and handles missing values
  - Boosted decision trees for improved accuracy

## 📈 Workflow

1. **Data Preprocessing**
   - Handle missing values (if any)
   - Normalize or scale features (optional)
   - Split data into training and test sets

2. **Model Training**
   - Train XGBoost Regressor on training data
   - Tune hyperparameters (if necessary)

3. **Evaluation**
   - Evaluate model using R² Score, RMSE, MAE
   - Plot feature importance and residuals

4. **Prediction**
   - Use the trained model to predict house prices on new/unseen data

## 📊 Results

| Metric | Value (Example) |
|--------|-----------------|
| R² Score | 0.89 |
| RMSE | 450000 |
| MAE | 300000 |

> *These are placeholder results. Replace with your actual evaluation metrics.*


