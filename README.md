# 🏠 Boston House Price Prediction

This project is a Machine Learning application that predicts house prices in Boston based on various features like the number of rooms, crime rate, and more. It uses the **Boston Housing Dataset** and applies a **Linear Regression** model to forecast housing prices.

---

## 📊 Project Overview

The main goal of this project is to:
- Understand the Boston housing dataset
- Perform data preprocessing and exploratory data analysis (EDA)
- Build and evaluate a linear regression model for predicting house prices
- Visualize results and model performance

---

## 📁 Dataset

The dataset used is the **Boston Housing Dataset** which contains information collected by the U.S Census Service concerning housing in the area of Boston, Massachusetts.

It includes 506 rows and 13 features like:
- CRIM — crime rate by town
- RM — average number of rooms per dwelling
- LSTAT — % lower status of the population
- TAX — property tax rate
- MEDV — median value of owner-occupied homes (target variable)

> ⚠️ Note: The original Boston dataset is deprecated in `scikit-learn` due to ethical concerns. For learning purposes, it's still used in this project.

---

## 🔧 Tech Stack

- Python 🐍
- NumPy
- Pandas
- Matplotlib & Seaborn (for EDA and visualization)
- scikit-learn (for model training)

---

## 🛠️ How to Run

1. Clone the repo:

bash
git clone https://github.com/your-username/boston-house-prediction.git
cd boston-house-prediction

2. Install the dependencies:
pip install -r requirements.txt

3. Run the notebook or Python script:
jupyter notebook
# or
python boston_prediction.py
