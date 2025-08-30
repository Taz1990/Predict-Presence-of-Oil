# Oil Reservoir Prediction using Machine Learning

This project predicts the **presence of oil reservoirs** using geological and trap features.  
It applies **data preprocessing, class balancing (SMOTE), and machine learning models** such as **Random Forest** and **XGBoost** to achieve accurate predictions.

---

## Features
- Handles missing values and categorical variables with encoding  
- Balances imbalanced dataset using **SMOTE (Synthetic Minority Oversampling)**  
- Trains and compares **Random Forest** and **XGBoost** classifiers  
- Evaluates models with **Classification Report** and **ROC-AUC**  

---

## Results
### Random Forest Results:
              precision    recall  f1-score   support

           0       0.90      0.94      0.92       722
           1       0.84      0.74      0.79       278
    accuracy                           0.89      1000
   macro avg       0.87      0.84      0.86      1000
weighted avg       0.89      0.89      0.89      1000

ROC-AUC: 0.8428027660973714

### XGBoost Results:
              precision    recall  f1-score   support

           0       0.90      0.92      0.91       722
           1       0.78      0.75      0.76       278
    accuracy                           0.87      1000
   macro avg       0.84      0.83      0.84      1000
weighted avg       0.87      0.87      0.87      1000

ROC-AUC: 0.8339345144383108

---

## Future Improvements

 - Hyperparameter tuning (GridSearch / Optuna)
 - Deployment with FastAPI
