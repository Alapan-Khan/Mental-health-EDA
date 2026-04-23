# Mental Health in Tech — EDA + ML Pipeline

## Overview
End-to-end data science project on the OSMI Mental Health in Tech 2016 survey (~1,400 respondents).
Predicts whether a tech worker has sought treatment for a mental health issue.

## What's in this project
- Purposeful EDA — every step driven by a hypothesis
- Data cleaning — age outlier removal, gender normalization (50+ raw values → 3 categories)
- Feature selection based on bivariate analysis and correlation
- 5 ML models compared: Logistic Regression, Decision Tree, Random Forest, XGBoost, SVM

## Key findings
- Family history and past/current disorder are the strongest predictors of treatment-seeking
- Workplace factors (benefits, wellness programs) have a weaker effect than personal/clinical history
- Women seek treatment at noticeably higher rates than men — consistent with external research

## Models & Metrics
Each model evaluated on Accuracy, Precision, Recall, F1, and AUC-ROC.
Confusion matrix and ROC curve included for every model.

## Dataset
[OSMI Mental Health in Tech 2016](https://www.kaggle.com/datasets/osmi/mental-health-in-tech-2016/data)

## Tech stack
Python, Pandas, Numpy, Matplotlib, Seaborn, Scikit-learn, XGBoost
