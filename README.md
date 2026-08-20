# Heart-Disease-Prediction
Heart Disease Prediction is a machine learning project using healthcare dataset. Built a Logistic Regression model with data preprocessing and age-category feature engineering to predict heart disease risk. **Tools:** Python, Pandas, NumPy, Scikit-learn, SQLite3.

The project follows a complete machine learning workflow, including data loading, data preprocessing, exploratory data analysis (EDA), feature engineering, model building, evaluation, and prediction.

A Logistic Regression model was selected as the final classification algorithm because it is simple, interpretable, and suitable for binary classification problems such as predicting whether a patient is at risk of heart disease.

🎯 Objective

The main objective of this project is to develop a machine learning model that can identify whether a patient is likely to have heart disease based on available health and demographic information.

The project also focuses on:

Understanding patterns in healthcare data
Cleaning and preparing a large dataset
Engineering meaningful features
Building and evaluating a classification model
Understanding the factors associated with heart disease risk

📊 Dataset

The dataset contains approximately 2 million healthcare records with patient-related information.

The dataset includes demographic and health-related features that can be used to identify patterns associated with heart disease.

Before model development, the data was checked for:

Missing values
Duplicate records
Incorrect data types
Inconsistent values
Outliers
Data quality issues

Data Preprocessing

The following preprocessing steps were performed:

Loaded and explored the dataset using Pandas.
Checked the structure and data types of the variables.
Identified and handled missing values where required.
Checked for duplicate records.
Performed exploratory analysis to understand the distribution of important variables.
Prepared categorical and numerical variables for machine learning.
Split the dataset into training and testing datasets.

Feature Engineering

Feature engineering was performed to improve the interpretability of the model.

One important feature created was an Age Category based on the patient's age:

Young
Middle-aged
Older

This transformation makes the relationship between age groups and heart disease risk easier to understand and provides a more meaningful representation of age for analysis.

Machine Learning Model
Logistic Regression

Logistic Regression was used as the classification algorithm.

The model predicts the probability of a patient belonging to a particular class, such as:

0 → No heart disease
1 → Heart disease

Logistic Regression was selected because it provides a relatively simple and interpretable approach for binary classification.

📈 Model Evaluation

The model was evaluated using appropriate classification metrics such as:

Accuracy
Precision
Recall
F1-score
Confusion Matrix

For a healthcare classification problem, Recall is particularly important, because identifying patients who may be at risk is an important consideration.
