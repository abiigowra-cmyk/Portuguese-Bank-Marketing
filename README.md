# Portuguese Bank Marketing Prediction

### Machine Learning Based Customer Term Deposit Subscription Prediction

## Project Overview

This project focuses on analysing Portuguese bank marketing campaign data and developing Machine Learning models to predict whether a customer will subscribe to a term deposit.

The main objective is to help banks identify potential customers and improve marketing campaign effectiveness.

## Problem Statement

Banks conduct marketing campaigns to attract customers to subscribe to term deposits. However, contacting every customer can be costly and time-consuming.

This project uses Machine Learning algorithms to predict customer subscription behaviour and support better marketing decisions.

## Project Objectives

- Perform Exploratory Data Analysis (EDA).
- Analyse customer behaviour and marketing campaign performance.
- Clean and preprocess the dataset.
- Build and compare Machine Learning models.
- Predict customer term deposit subscriptions.
- Provide business recommendations to improve campaign effectiveness.

## Dataset Information

**Dataset:** Portuguese Bank Marketing Dataset

**Source:** UCI Bank Marketing Dataset

**Target Variable:** `y`

- `yes` – Customer subscribed to a term deposit.
- `no` – Customer did not subscribe.

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost

## Machine Learning Algorithms

The following algorithms were implemented and compared:

1. Logistic Regression
2. Decision Tree Classifier
3. Random Forest Classifier
4. XGBoost Classifier

**Final Selected Model:** XGBoost Classifier

Model selection considered evaluation metrics such as Precision, Recall, F1-score, ROC-AUC and PR-AUC.

## Data Preprocessing

- Handling missing and unknown values.
- Encoding categorical variables.
- Scaling numerical features.
- Feature engineering.
- Stratified train-test splitting.
- Handling class imbalance using class weights.

The `duration` feature was excluded to avoid data leakage during realistic pre-call prediction.

## Model Evaluation

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- ROC-AUC
- PR-AUC
- Confusion Matrix

Threshold optimization was also performed to improve prediction performance.

## Business Recommendations

- Focus marketing campaigns on customers with higher subscription potential.
- Improve campaign timing and communication strategies.
- Avoid contacting customers excessively.
- Analyse previous campaign outcomes.
- Use predictive insights to optimize marketing resources.

## Project Structure

```text
Portuguese-Bank-Marketing/
│
├── Data/
│   └── bank-additional-full.csv
│
├── models/
│   ├── Portuguese_Bank_XGBoost_Model.pkl
│   └── best_threshold.pkl
│
├── notebook/
│   └── Portuguese_Bank_Marketing.ipynb
│
└── README.md
```

## How to Run the Project

1. Clone this repository.
2. Install the required Python libraries.
3. Open Jupyter Notebook.
4. Navigate to the `notebook` folder.
5. Open `Portuguese_Bank_Marketing.ipynb`.
6. Run all cells.

## Conclusion

This project demonstrates how Machine Learning can be applied to banking marketing data to predict customer subscription behaviour.

The developed XGBoost model and comparative analysis provide useful insights that can help improve marketing campaign efficiency and customer targeting.

---

**Project Domain:** Banking / Finance

**Project Type:** Data Science & Machine Learning
