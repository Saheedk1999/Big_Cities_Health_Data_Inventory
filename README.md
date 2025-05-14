# 🩺 Big Cities Health Data Inventory - Machine Learning Project

## 📌 Project Description
This project uses the Big Cities Health Inventory dataset to build and evaluate multiple regression models. The goal is to predict health-related metrics using various features from the dataset.

### 📊 Dataset
Source: Big Cities Health Inventory Data
#### Summary
This dataset illustrates health status of 26 of the nation’s largest and most urban cities as captured by 34 health (and six demographics-related) indicators. These indicators represent some of the leading causes of morbidity and mortality in the United States and leading priorities of national, state, and local health agencies. Public health data were captured in nine overarching categories: HIV/AIDS, cancer, nutrition/physical activity/obesity, food safety, infectious disease, maternal and child health, tobacco, injury/violence, and behavioral health/substance abuse.

### 🔄 ML Pipeline

 Data Collection – Big Cities Health Inventory dataset.
 Data Cleaning & Preprocessing– Missing value handling, normalization, PCA.
 Exploratory Data Analysis (EDA) – Correlation heatmaps, pair plots.
 Model Building – Applied:
    - Linear Regression
    - Decision Tree Regressor
    - Random Forest Regressor
    - Gradient Boosting Regressor
    - XGBoost Regressor
    - KNN Regressor
    - SVR (with scaling)

#### Model Evaluation – Metrics used:
  - R² Score
   - RMSE
   - Cross-validation (5-fold)

### ⚙️ Tools Used

- **Language:** Python
- Libraries:
- pandas, numpy
- scikit-learn, xgboost
- matplotlib, seaborn
