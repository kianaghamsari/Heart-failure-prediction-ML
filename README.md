# Heart Failure Prediction using Machine Learning

A machine learning project focused on predicting the risk of heart failure
based on clinical patient data using classical ML models and a full data science pipeline.

> This project was originally developed as part of an academic course and later refined for public release.

---

## Problem Statement
Heart failure is a critical medical condition where early risk detection can significantly improve patient outcomes.
The goal of this project is to predict the likelihood of heart failure using clinical features such as age,
ejection fraction, blood pressure, and medical history.

---

## Approach

### Data Processing
- Exploratory data analysis (EDA)
- Handling categorical and numerical features
- Feature scaling and encoding
- Correlation analysis

### Models Evaluated
- Logistic Regression
- Decision Tree
- Support Vector Machine (SVM)
- XGBoost

### Model Selection
- Hyperparameter tuning using GridSearchCV
- Evaluation using Accuracy, Precision, Recall, F1-score
- ROC and AUC analysis
- Training time comparison


### Model Interpretation
- Feature importance analysis for model interpretability


---

## Dimensionality Reduction & Visualization
- Principal Component Analysis (PCA)
- t-SNE for data visualization
- KMeans clustering for pattern exploration

---

## Results
- XGBoost achieved the best overall performance
- ROC-AUC analysis showed strong class separation
- Feature importance analysis highlighted key clinical indicators

---

## Tech Stack
- Python
- NumPy, Pandas
- Scikit-learn
- XGBoost
- Matplotlib, Seaborn


---

## Notes
This project focuses on analysis and modeling rather than deployment.
Future extensions may include API integration or clinical decision support tools.
