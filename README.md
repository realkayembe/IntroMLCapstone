# House Prices – Advanced Regression Techniques: ML Capstone

This project tackles the **House Prices – Advanced Regression Techniques** Kaggle competition dataset.  
The main goal is to predict house sale prices using a mix of **classical machine learning models** and **ensemble-based methods from recent literature**, then compare their performance.

The is the capstone project for the course.

---

## 1. Dataset
- **Name:** House Prices – Advanced Regression Techniques (Kaggle)
- **Target variable:** SalePrice
- **Features:** 79 explanatory variables.
- **File used:** train.csv  

Each notebook performs its own preprocessing and splits the data 80/20 for training and validation.

---

## 2. Models Implemented
### Classical Models
1. Linear Regression  
2. Lasso Regression  
3. Neural Network Regression (MLP)

### Literature-Based Models
4. Random Forest Regressor  
5. XGBoost Regressor  

---

## 3. Repository Structure
```
01_linear_regression.ipynb
02_lasso_regression.ipynb
03_neural_network_regression.ipynb
04_random_forest_paper1.ipynb
05_xgboost_paper2.ipynb
train.csv
README.md
```

---

## 4. Dependencies
```
pip install numpy pandas scikit-learn matplotlib xgboost
```

---

## 5. Results Summary
| Model                     | MSE           | MAE       |
|---------------------------|---------------|-----------|
| Linear Regression         | 868,752,504.74 | 18,287.63 |
| Lasso Regression          | 797,537,164.48 | 17,921.06 |
| Neural Network Regression | 1,509,930,924.66 | 22,116.44 |
| Random Forest (Paper 1)   | 836,151,522.08 | 17,647.42 |
| XGBoost (Paper 2)         | 649,695,978.71 | 15,764.20 |

---

## 6. Notes
- XGBoost performed the best.
- Neural Network underperformed compared to ensemble models.
- Random Forest and Lasso improved over Linear Regression.
