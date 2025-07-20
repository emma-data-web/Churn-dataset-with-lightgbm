# Churn-dataset-with-lightgbm
Predicting customer churn using LightGBM on the Telco Customer Churn Dataset.

🚀 Project Overview
This project demonstrates:
✅ End-to-end machine learning workflow on a real-world churn dataset
✅ Data cleaning and leakage handling
✅ Feature engineering and categorical handling
✅ LightGBM model training with GridSearchCV hyperparameter tuning
✅ Model evaluation with classification report, confusion matrix, ROC-AUC
✅ SHAP for model interpretability
✅ Best practices for robust ML pipelines

🗂️ Dataset
Telco Customer Churn dataset

~7,000+ samples

Categorical and numerical features including:

Customer demographics

Contract and billing information

Service usage data

Target: Churn Label (Yes/No)

⚙️ Key Libraries
pandas, numpy

scikit-learn

lightgbm

shap

matplotlib, seaborn

🛠️ Project Steps
✅ 1️⃣ Data Cleaning:

Removed leakage columns (Churn Value, CLTV, etc.)

Handled categorical and numerical columns appropriately

Managed missing values in Total Charges

✅ 2️⃣ Feature Engineering:

Split LatLon into Latitude and Longitude

Encoded categorical variables using OneHotEncoder within a pipeline

✅ 3️⃣ Model Building:

Built a LightGBM Classifier within a Pipeline and ColumnTransformer

Used GridSearchCV with 5-fold CV for hyperparameter tuning

✅ 4️⃣ Evaluation:

Accuracy, precision, recall, F1-score

Confusion Matrix

ROC-AUC Score

✅ 5️⃣ Model Interpretation:

Used SHAP to interpret LightGBM feature importances and individual predictions.

📊 Results
Achieved ~98% accuracy on the test set.

ROC-AUC Score: ~0.99, indicating strong predictive performance.

Visualized feature importances to understand top churn drivers.

Author -- Nwankwo Emmanuel Ota
