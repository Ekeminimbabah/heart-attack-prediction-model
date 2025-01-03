# heart-attack-prediction-model
# Project Overview
This project aims to predict the likelihood of a heart attack using machine learning techniques. The dataset contains various health metrics, and the model is designed to assist in identifying high-risk individuals based on their medical attributes.

# Features
# Exploratory Data Analysis (EDA):
Understand the dataset structure, handle missing values, and visualize key features.
# Data Preprocessing: 
Address missing data and imbalances in the dataset.
# Model Training and Optimization: 
Implement multiple machine learning models and tune hyperparameters for optimal performance.   
# Evaluation:
Assess the models' performance using metrics such as accuracy and classification reports.
# Dataset
The dataset used for this project contains information about heart health metrics. It includes features like age, cholesterol levels, blood pressure, and more. Null values in the dataset were addressed by cleaning techniques "Dropping null".

# Project Workflow
Data Loading: The dataset is loaded into a pandas DataFrame for processing.

#Exploratory Data Analysis:  

Checked for null values.  
Performed statistical summaries.  
Visualized distributions and correlations between features.  
Data Cleaning:  

Removed rows with missing values.
Addressed class imbalance using SMOTE (Synthetic Minority Over-sampling Technique).  
Model Development:  

Logistic Regression
Random Forest Classifier
Support Vector Machine (SVM)
Hyperparameter tuning using GridSearchCV.
Evaluation:

Metrics used include accuracy score and classification reports.  
# Requirements  
To run this project, the following libraries are required:    

Python 3.x,  
pandas,  
numpy,  
seaborn,  
matplotlib,  
scikit-learn,  
imbalanced-learn
