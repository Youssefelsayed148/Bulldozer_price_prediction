# Bulldozer_price_prediction
This project predicts the sale price of used bulldozers using machine learning.
## 🔍 Problem Overview

- **Dataset**: Historic auction data for bulldozers.
- **Target Variable**: `SalePrice` (the price at which a bulldozer sold)
- **Goal**: Predict future bulldozer prices based on features such as model ID, year sold, machine hours, etc.

---

## ⚙️ Machine Learning Approach

### ✅ Preprocessing
- Missing value imputation
- Ordinal encoding for categorical features
- Feature selection
- Pipelines for clean, reproducible ML flow

### ✅ Models Trained
- **Linear Regression**
- **Random Forest Regressor**
- **XGBoost Regressor** (best performer)

### 📦 Model Pipelines Saved:
Each model pipeline includes preprocessing + model:

## 📊 Evaluation Metrics

- **Root Mean Squared Log Error (RMSLE)**
- **R² Score**
- **Mean Absolute Error (MAE)**

---
