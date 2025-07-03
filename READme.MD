# 🏠 House Price Prediction – Regression Project

This project uses the **Ames Housing Dataset** to predict house sale prices using a `RandomForestRegressor`. It involves cleaning, encoding, scaling, model training, evaluation, and feature interpretation.

---

## 📌 Project Goals

- Predict house prices accurately using regression models
- Identify the most important factors influencing house prices
- Evaluate model performance using MAE, RMSE, and R²

---

## 📊 Dataset Info

- 📂 Source: [Ames Housing Dataset on Kaggle](https://www.kaggle.com/datasets/prevek18/ames-housing-dataset)
- 🧮 80+ features (numerical and categorical)
- 🎯 Target: `SalePrice`

---

## 🧼 Preprocessing Steps

- Missing values handled using:
  - Median for numerical columns
  - Mode for categorical columns
- One-hot encoding for categorical variables
- Scaled using `MinMaxScaler`

---

## 🤖 Model Used

- `RandomForestRegressor` from scikit-learn

### 📈 Performance on Test Set:
- **MAE**: 0.0214
- **RMSE**: 0.0358
- **R²**: 0.9118 ✅

---

## 🔍 Top 3 Most Important Features

| Feature        | Meaning                                      |
|----------------|----------------------------------------------|
| `OverallQual`  | Overall material and finish quality          |
| `GrLivArea`    | Above-ground living area (sq ft)             |
| `1stFlrSF`     | First floor square footage                   |

---

## 📎 Requirements

```bash
pandas
numpy
scikit-learn
seaborn
matplotlib