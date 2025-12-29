🔁 Task 2: End-to-End ML Pipeline with Scikit-learn

🎯 Objective

To design a production-ready and reusable machine learning pipeline for predicting customer churn, with special emphasis on preventing data leakage.

🛠 Methodology / Approach

Dataset: Telco Customer Churn Dataset

Pipeline Design:

Used ColumnTransformer and Pipeline API

Applied StandardScaler for numerical features

Used OneHotEncoder for categorical features

Model Selection:

Compared Logistic Regression and Random Forest

Performed hyperparameter tuning using GridSearchCV

Export:

Serialized the final pipeline into a .pkl file using joblib for deployment

📊 Key Results & Observations

Best Model: Logistic Regression with ~80.7% cross-validation accuracy

Insight: The Pipeline API enabled seamless handling of raw input data during inference, ensuring full production readiness
