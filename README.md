# SNAP_Expenditure_Prediction
## Predicting County-Level SNAP Expenditures Using Lasso and Decision Tree Models

---

##  Project Overview  
This project applies machine learning techniques to predict county-level SNAP (Supplemental Nutrition Assistance Program) expenditures using administrative and fiscal indicators. Two regression models—**Lasso Regression** and **Decision Tree Regression**—are implemented and compared to evaluate their predictive performance.

---

## Objectives  
- Predict total SNAP expenditure (`Cell_30`) from program indicators.  
- Compare linear (Lasso) and nonlinear (Decision Tree) models.  
- Identify key factors influencing SNAP spending.  
- Evaluate models using R², MSE, and MAE metrics.

---

## Dataset Description  
- **Observations:** 10,384 county-level records  
- **Features:** 31 numeric indicators (`Cell_1`–`Cell_29`, FFY, County_Code)  
- **Target:** `Cell_30` – Total SNAP expenditure (USD)  
- Currency values were cleaned and converted to numeric format.

---

## Methods Used  
- Data cleaning and preprocessing  
- Train-test split (80/20)  
- **Lasso Regression** with feature scaling and L1 regularization  
- **Decision Tree Regression** with depth constraints  
- Performance evaluation using:  
  - R² (Coefficient of Determination)  
  - Mean Squared Error (MSE)  
  - Mean Absolute Error (MAE)

---

## Key Results  
- **Lasso Regression:** R² ≈ 0.9999 with the lowest error metrics  
- **Decision Tree Regression:** R² ≈ 0.9961 with significantly higher errors  
- Lasso outperformed the Decision Tree and identified multiple important predictors, indicating strong linear relationships in the data.

---

## Conclusion  
Lasso Regression provided superior predictive accuracy for SNAP expenditures, demonstrating that county-level SNAP costs are strongly driven by linear relationships among administrative indicators. The findings highlight the value of regularized regression methods for public policy analysis and financial forecasting.

---

##  Course Information  
**Course:** STAT-6000 – Intermediate Statistical Methods for Data Science 
  

---
