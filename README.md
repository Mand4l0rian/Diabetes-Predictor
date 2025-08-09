# Overview:

This project predicts the likelihood of diabetes using the PIMA Indians Diabetes Dataset with an enhanced logistic regression model.
It incorporates advanced preprocessing, class-specific missing value imputation, outlier handling, feature engineering, and hyperparameter tuning to improve prediction accuracy and interpretability.


# Dataset:

1) Source: PIMA Indians Diabetes Dataset

2) Features: 8 medical attributes (e.g., Glucose, BMI, Age)

3) Target: Diabetes outcome (0 = No, 1 = Yes)

# Key Features:

1) Class-specific median imputation for missing values

2) Winsorization for outlier handling

3) Interaction, ratio, and polynomial feature creation

4) Clinically relevant features such as HOMA-IR

5) RobustScaler for scaling to handle outliers

6) Logistic Regression with hyperparameter tuning using GridSearchCV

7) Evaluation using Accuracy, F1 Score, and ROC-AUC metrics

8) Feature importance analysis and visualization

# Installation and Usage:
```
#Clone the repository
git clone https://github.com/yourusername/diabetes-prediction-logistic.git
cd diabetes-prediction-logistic

#Install dependencies
pip install -r requirements.txt

#Run the script
python diabetes_prediction.py
```
