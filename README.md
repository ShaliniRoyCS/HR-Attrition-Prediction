# HR-Attrition-Prediction
This project analyzes HR data to identify patterns and predict employee attrition using machine learning models. It includes data preprocessing, exploratory data analysis, model training, and evaluation, helping organizations take proactive measures to retain valuable talent.
# Introduction
This project analyzes employee data from the Human Resources department to understand patterns and factors associated with employee attrition. Using various machine learning models, the goal is to predict which employees are likely to leave the company, helping the organization to take proactive measures to retain valuable talent.
# Dataset
The dataset used in this project is the Human Resources data which includes features such as age, daily rate, distance from home, education, environment satisfaction, gender, job role, marital status, and more. The target variable is 'Attrition' indicating whether an employee left the company or not.
# Installation
To run this project, you need to have Python installed along with the following libraries:

pandas
numpy
seaborn
matplotlib
scikit-learn
tensorflow (for deep learning)
# Data Preprocessing
Converted categorical columns like 'Attrition' and 'OverTime' into numerical values.
Dropped irrelevant columns such as 'EmployeeCount', 'StandardHours', 'Over18', and 'EmployeeNumber'.
One-hot encoded categorical features.
Scaled numerical features using MinMaxScaler.
# Exploratory Data Analysis
Visualized missing data using a heatmap.
Generated histograms for numerical features.
Created count plots for features like 'Age', 'JobRole', 'MaritalStatus', 'JobInvolvement', and 'JobLevel' to understand their distribution with respect to attrition.
Analyzed correlations between features and generated a heatmap.
# Modeling
We implemented and compared the performance of three models:

Logistic Regression
Random Forest Classifier
Deep Learning Model using TensorFlow
