Overview
This project predicts the likelihood of diabetes using the PIMA Indians Diabetes Dataset with an enhanced logistic regression model.
It incorporates advanced preprocessing, class-specific missing value imputation, outlier handling, feature engineering, and hyperparameter tuning to improve prediction accuracy and interpretability.

Dataset
Source: PIMA Indians Diabetes Dataset

Features: 8 medical attributes (e.g., Glucose, BMI, Age)

Target: Diabetes outcome (0 = No, 1 = Yes)

Key Features
Class-specific median imputation for missing values

Winsorization for outlier handling

Interaction, ratio, and polynomial feature creation

Clinically relevant features such as HOMA-IR

RobustScaler for scaling to handle outliers

Logistic Regression with hyperparameter tuning using GridSearchCV

Evaluation using Accuracy, F1 Score, and ROC-AUC metrics

Feature importance analysis and visualization
