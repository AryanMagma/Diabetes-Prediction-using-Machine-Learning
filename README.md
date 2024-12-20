# Diabetes-Prediction-using-Machine-Learning
## Overview
Predicting diabetes using machine learning is a significant healthcare challenge. This project utilizes a Logistic Regression model to predict whether a patient has diabetes based on various features, such as the number of pregnancies, BMI, insulin levels, and age. By leveraging machine learning techniques, the study aimed to create robust classification models for predicting diabetes and maximizing validation scores.

## Motivation
Working with healthcare data presents unique challenges and opportunities. Having previously analyzed numerical datasets, this project provided an opportunity to delve into healthcare data and explore its potential for predictive modeling. The complexity of preprocessing and building machine learning models for this domain offered an enriching experience.

## **Objectives of the Project**
1. Reading and analyzing the Diabetes Dataset.
2. Conducting Exploratory Data Analysis (EDA):
   - Examining the structure of the dataset.
   - Inspecting variable types and dataset dimensions.
   - Identifying missing values and replacing them with `NaN`.
   - Reviewing descriptive statistics.
3. Data Preprocessing:
   - Filling missing observations with median values for respective conditions.
   - Identifying and removing outliers using the LOF method.
   - Standardizing independent variables using the robust method.
4. Model Building:
   - Developing multiple machine learning models, including Logistic Regression, KNN, SVM, CART, Random Forests, XGBoost, and LightGBM.
   - Computing Cross Validation Scores for model evaluation.
   - Optimizing Random Forests, XGBoost, and LightGBM models through hyperparameter tuning to improve validation scores.
5. Result Analysis:
   - Selecting the model with the best performance based on Cross Validation Scores.
   - Achieving the highest performance with the XGBoost model after hyperparameter optimization, with a score of **0.90**.
  



### **Technologies Used**
- **Programming Languages:** Python
- **Libraries:** Pandas, NumPy, Scikit-learn, XGBoost, LightGBM, Matplotlib, Seaborn
- **Tools:** Jupyter Notebook


### **Author**
Aryan Singh

### **Credits**
- Open-source datasets and resources.
- Python machine learning community for helpful tutorials and libraries.
