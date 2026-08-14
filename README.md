🏦 Bank Customer Churn Prediction | Machine Learning
📌 Project Overview

An end-to-end machine learning project to predict whether a bank customer is likely to churn (exit) based on customer demographics, account information, and banking behavior.

The project uses 10,000 customer records and covers exploratory data analysis, data preprocessing, feature encoding, model training, evaluation, and model comparison.

🎯 Objective

The main objective is to identify customers who are likely to leave the bank and determine which classification model performs best for churn prediction.

🛠️ Tech Stack

Python | Pandas | NumPy | Matplotlib | Seaborn | Scikit-learn | Jupyter Notebook

🔍 Exploratory Data Analysis

The project analyzes:

Churn distribution
Age vs. churn
Churn by geography
Correlation between numerical variables
Visualizations
Churn Distribution
Age vs Churn
Churn by Geography
Correlation Heatmap
Model Comparison
Random Forest Feature Importance
Random Forest Confusion Matrix
🧹 Data Preprocessing

The following steps were performed:

Removed irrelevant columns: RowNumber, CustomerId, and Surname
Encoded Geography and Gender using LabelEncoder
Separated features (X) and target (y)
Used an 80/20 stratified train-test split
Applied StandardScaler for Logistic Regression
🤖 Machine Learning Models

Three classification models were trained and compared:

Logistic Regression
Decision Tree
Random Forest

The Random Forest model was configured with 100 estimators.

📊 Model Evaluation

Models were evaluated using:

Accuracy
Precision
Recall
F1 Score
RMSE
Classification Report
Confusion Matrix

Models were compared using Accuracy, F1 Score, and RMSE, with the comparison ranked by F1 Score.

🔎 Feature Importance

Random Forest feature importance was used to identify the customer attributes that contributed most to churn predictions.

💡 Business Value

The analysis can help banks:

Identify customers at higher risk of churn
Understand factors associated with customer exit
Prioritize customer retention efforts
Compare machine learning models for churn prediction
🔄 Project Workflow

Customer Data
↓
Data Loading & Inspection
↓
Exploratory Data Analysis
↓
Data Preprocessing
↓
Categorical Encoding
↓
Feature & Target Separation
↓
Stratified Train-Test Split
↓
Feature Scaling
↓
Model Training
↓
Model Evaluation
↓
Model Comparison
↓
Feature Importance
↓
Confusion Matrix
↓
Churn Prediction

📁 Project Structure

Bank-Customer-Churn-Prediction/

├── data/
│ └── churn.csv
│
├── notebook/
│ └── Bank Customer Churn Prediction.ipynb
│
├── visualizations/
│ ├── churn_distribution.png
│ ├── age_vs_churn.png
│ ├── churn_by_geography.png
│ ├── correlation_heatmap.png
│ ├── model_comparison.png
│ ├── feature_importance.png
│ └── confusion_matrix.png
│
└── README.md

🎓 Key Learning

This project demonstrates practical skills in data preprocessing, exploratory data analysis, feature encoding, classification, model evaluation, feature importance, and applying machine learning to a real-world customer retention problem.

👤 Author
Jeevan S J
Data Analyst | Data Science | Python | SQL | Power BI | Excel | Machine Learning | AI-ML | Business Intelligence
