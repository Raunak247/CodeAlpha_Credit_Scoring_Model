# CodeAlpha_Credit_Scoring_Model

# Credit Scoring Model

This project focuses on predicting whether a person is creditworthy based on their financial data.

## 📌 Overview
The goal is to build a simple classification model using historical financial information such as income, debts, and payment behavior.

## ⚙️ Approach
- Cleaned the dataset by removing missing values
- Split data into training and testing sets
- Applied feature scaling using StandardScaler
- Used Logistic Regression for classification

## 📊 Evaluation
Model performance is evaluated using:
1. Logistic Regression
- Accuracy : 0.5369350915375752
  
-            precision    recall  f1-score   support

           0       0.37      0.03      0.06      1240
           1       0.51      0.28      0.36      2409
           2       0.54      0.84      0.66      4162

    accuracy                           0.54      7811
   macro avg       0.48      0.38      0.36      7811
weighted avg       0.51      0.54      0.47      7811

- ROC-AUC score :  0.6643477048150689
  
2. DecisionTreeClassifier
- Accuracy :  0.6688004096786583

-               precision    recall  f1-score   support

           0       0.58      0.56      0.57      1240
           1       0.64      0.65      0.65      2409
           2       0.71      0.71      0.71      4162

    accuracy                           0.67      7811
   macro avg       0.64      0.64      0.64      7811
weighted avg       0.67      0.67      0.67      7811

- ROC-AUC score : 0.7260403081189079

3. RandomForestClassifier
- RF Accuracy: 0.7740366150300858
              precision    recall  f1-score   support

           0       0.69      0.71      0.70      1240
           1       0.76      0.79      0.78      2409
           2       0.81      0.78      0.79      4162

    accuracy                           0.77      7811
   macro avg       0.75      0.76      0.76      7811
weighted avg       0.78      0.77      0.77      7811

- RF ROC AUC Score: 0.8948351416849945

## 🛠️ Technologies Used
- Python
- Pandas
- Scikit-learn

## ▶️ How to Run
1. Place the dataset file (`credit_data.csv`) in the same folder  
2. Run the script:
