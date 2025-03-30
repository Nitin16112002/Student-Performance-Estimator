# Student Performance Estimator

## Overview
This project aims to estimate student performance using various regression models. It evaluates the effectiveness of different machine learning algorithms based on key performance metrics such as RMSE, MAE, and R² score.

## Models and Performance Metrics

### **1. Linear Regression**
#### Training Set:
- **Root Mean Squared Error:** 5.3303  
- **Mean Absolute Error:** 4.2733  
- **R² Score:** 0.8740  

#### Test Set:
- **Root Mean Squared Error:** 5.4238  
- **Mean Absolute Error:** 4.2231  
- **R² Score:** 0.8791  

---

### **2. Lasso Regression**
#### Training Set:
- **Root Mean Squared Error:** 6.5938  
- **Mean Absolute Error:** 5.2063  
- **R² Score:** 0.8071  

#### Test Set:
- **Root Mean Squared Error:** 6.5197  
- **Mean Absolute Error:** 5.1579  
- **R² Score:** 0.8253  

---

### **3. Ridge Regression**
#### Training Set:
- **Root Mean Squared Error:** 5.3233  
- **Mean Absolute Error:** 4.2650  
- **R² Score:** 0.8743  

#### Test Set:
- **Root Mean Squared Error:** 5.3904  
- **Mean Absolute Error:** 4.2111  
- **R² Score:** 0.8806  

---

### **4. K-Neighbors Regressor**
#### Training Set:
- **Root Mean Squared Error:** 5.7079  
- **Mean Absolute Error:** 4.5168  
- **R² Score:** 0.8555  

#### Test Set:
- **Root Mean Squared Error:** 7.2530  
- **Mean Absolute Error:** 5.6210  
- **R² Score:** 0.7838  

---

### **5. Decision Tree**
#### Training Set:
- **Root Mean Squared Error:** 0.2795  
- **Mean Absolute Error:** 0.0187  
- **R² Score:** 0.9997  

#### Test Set:
- **Root Mean Squared Error:** 8.1391  
- **Mean Absolute Error:** 6.3850  
- **R² Score:** 0.7278  

---

### **6. Random Forest Regressor**
#### Training Set:
- **Root Mean Squared Error:** 2.2964  
- **Mean Absolute Error:** 1.8332  
- **R² Score:** 0.9766  

#### Test Set:
- **Root Mean Squared Error:** 6.0296  
- **Mean Absolute Error:** 4.6653  
- **R² Score:** 0.8506  

---

### **7. XGB Regressor**
#### Training Set:
- **Root Mean Squared Error:** 0.9087  
- **Mean Absolute Error:** 0.6148  
- **R² Score:** 0.9963  

#### Test Set:
- **Root Mean Squared Error:** 6.5889  
- **Mean Absolute Error:** 5.0844  
- **R² Score:** 0.8216  

---

### **8. CatBoost Regressor**
#### Training Set:
- **Root Mean Squared Error:** 3.0427  
- **Mean Absolute Error:** 2.4054  
- **R² Score:** 0.9589  

#### Test Set:
- **Root Mean Squared Error:** 6.0086  
- **Mean Absolute Error:** 4.6125  
- **R² Score:** 0.8516  

---

### **9. AdaBoost Regressor**
#### Training Set:
- **Root Mean Squared Error:** 5.8092  
- **Mean Absolute Error:** 4.7588  
- **R² Score:** 0.8503  

#### Test Set:
- **Root Mean Squared Error:** 6.1564  
- **Mean Absolute Error:** 4.8536  
- **R² Score:** 0.8442  

---

## Conclusion
- **Linear Regression and Ridge Regression** performed well with high R² scores, making them reliable models.
- **Random Forest and CatBoost Regressors** showed strong generalization capability with good test performance.
- **Decision Tree and K-Neighbors Regressor** suffered from overfitting, leading to poor test set performance.
- **XGB Regressor had exceptional training performance but slightly lower test accuracy.**
- **Lasso Regression** underperformed compared to Ridge and Linear Regression.
- **AdaBoost showed decent performance but was slightly outperformed by CatBoost.**

## Future Improvements
- **Feature Engineering:** Enhancing dataset features could improve model performance.
- **Hyperparameter Tuning:** Further optimization may yield better results.
- **Stacking Models:** Combining multiple regressors may enhance predictive power.

---
