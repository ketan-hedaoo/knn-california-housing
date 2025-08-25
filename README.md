# 🏡 KNN Regression on California Housing Dataset

## 📌 Project Overview  
This project demonstrates how **K-Nearest Neighbors (KNN) regression** can be applied to the **California Housing dataset**.  
We build a baseline model, perform hyperparameter tuning, and evaluate performance using standard regression metrics.  

---

## 📂 Repository Structure
```
├── notebooks/
├── outputs/
  ├── eda/
  ├── models/
```

---

## 🚀 Steps Covered
1. **Dataset Loading** – California Housing dataset from `sklearn.datasets`.  
2. **Exploratory Data Analysis (EDA)** – Basic statistics & feature-target distributions.  
3. **Preprocessing** – Train-test split and feature scaling (StandardScaler).  
4. **Modeling** – KNN Regressor as baseline.  
5. **Hyperparameter Tuning** – GridSearchCV for `n_neighbors` and `metric`.  
6. **Evaluation** – RMSE, MSE, and R² comparison before and after tuning.  

---

## 📦 Key Libraries
- Python 3.8+
- scikit-learn
- pandas
- numpy
- matplotlib
- seaborn

---

## 📊 Results
| Model        | RMSE   | MSE    | R²      |
|--------------|--------|--------|---------|
| Baseline KNN | 1.1487 | 0.8946 | -0.0069 |
| Tuned KNN    | 0.6107 | 0.4161 | 0.7154  |

