# Coronary Heart Disease (CHD) Risk Prediction

A machine learning project that predicts a patient's 10-year risk of 
developing coronary heart disease (CHD) using health and lifestyle data.

## What it does
- Cleans and preprocesses real-world patient health data (~3,650 records)
- Handles class imbalance using SMOTE (Synthetic Minority Over-sampling)
- Engineers new features (age–blood pressure interaction, cholesterol-to-age ratio)
  to improve prediction accuracy
- Trains and compares 6 models: XGBoost, Random Forest, CatBoost, 
  Logistic Regression, SVM, and a Deep Learning (Neural Network) model
- Evaluates models using Accuracy, AUC-ROC, Confusion Matrix, and 
  Classification Reports

## Results
| Model               | Accuracy | AUC   |
|---------------------|----------|-------|
| XGBoost             | 81.4%    | 0.688 |
| Random Forest       | 77.2%    | 0.698 |
| CatBoost            | 75.9%    | 0.673 |
| Deep Learning (NN)  | 79.0%    | -     |
| SVM                 | 68.3%    | 0.643 |
| Logistic Regression | 64.4%    | 0.674 |

XGBoost achieved the highest accuracy, while Random Forest had the 
best AUC score.

## Tech used
- Python
- pandas, numpy, matplotlib, seaborn
- scikit-learn, XGBoost, CatBoost
- imbalanced-learn (SMOTE)
- TensorFlow / Keras

## Dataset
Framingham Heart Study dataset (public health dataset used for CHD 
risk research).

## How to run
Open the notebook file in Google Colab or Jupyter Notebook and run 
all cells in order.
