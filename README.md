# 🏠 Boston House Price Prediction (ML Project)

This repository contains a machine learning model that predicts housing prices in Boston using the **Gradient Boosting Regressor** algorithm. It demonstrates data preprocessing, feature scaling, visualization, and model training using the popular `BostonHousing.csv` dataset.

---

## 📁 Dataset

The dataset contains various features that affect housing prices, such as:

- `crim` — crime rate by town
- `rm` — average number of rooms per dwelling
- `lstat` — % lower status of the population
- `tax`, `rad`, `nox`, etc.
- `medv` — median value of owner-occupied homes (target)

📌 Note: Missing values are handled using `SimpleImputer`.

---

## 🔍 Project Workflow

1. **Data Cleaning**
   - Removed null values using `dropna()` and `SimpleImputer`

2. **EDA**
   - Correlation heatmap using `Seaborn` to understand feature relationships

3. **Preprocessing**
   - Standardized features using `StandardScaler`
   - Split data into training and test sets (`90/10` split)

4. **Modeling**
   - Trained a `GradientBoostingRegressor` for prediction
   - Optionally tested other models (RandomForest, Linear Regression)

---

## 🔧 Technologies Used

- Python 3
- Pandas, NumPy
- Seaborn, Matplotlib
- Scikit-learn

---

## 📈 Model Evaluation

Model: **Gradient Boosting Regressor**  
Split: 90% training, 10% testing  
Evaluation metrics like R² score or MSE can be printed using `sklearn.metrics`

You can later improve it by:
- Trying ensemble models like RandomForest or XGBoost
- Using GridSearchCV for hyperparameter tuning
- Deploying it using Flask or Streamlit

---

## 🚀 Getting Started

### Clone the repository

```bash
git clone https://github.com/YOUR-USERNAME/boston-house-price-prediction.git
cd boston-house-price-prediction
