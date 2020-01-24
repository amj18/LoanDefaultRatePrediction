## Loan Default Rate Prediction using Kaggle Lending Club Data
### Overview
- Loading of Kaggle Lending Club Loan Dataset (2 GB+ directly into memory - takes a couple of seconds to load on my desktop machine with 32 GB RAM) - (Generally not the most efficient approach and cloud computing or spark should have been used)
- Data cleaning (mean imputation of missing values in categorical and numerical columns)
- Model training and evaluation (Logistic Regression, PCA and Gradient Boosting Classifier)
- Key evaluation metrics tested: ROC-AUC, Precision/Recall curves, Confusion Matrix
