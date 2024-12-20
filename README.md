# Heart Disease Prediction Using Machine Learning
Project Description
This project aims to build a robust machine learning pipeline to predict the presence of heart disease based on patient health indicators. The project tackles uncleaned data, performs comprehensive data preprocessing, and implements several machine learning models to determine the most effective algorithm.

Additionally, the final model is deployed to provide an interactive tool or API that can be used in real-world healthcare scenarios.

#Key Objectives
Data Cleaning and Preprocessing:
Handling missing values, outliers, and inconsistencies in the dataset.
Normalizing and encoding data for compatibility with machine learning algorithms.
Exploratory Data Analysis (EDA):
Understanding correlations between features and the target variable.
Using visualization tools like Matplotlib and Seaborn for insights.
Model Implementation:
Training multiple machine learning models such as Logistic Regression, Random Forest, Support Vector Machines (SVM), and Neural Networks.
Performing hyperparameter tuning to optimize model performance.
Evaluation:
Comparing models using metrics such as accuracy, precision, recall, F1-score, and ROC-AUC.
Deployment:
Converting the final model into an interactive application using Flask, FastAPI, or Streamlit.
Hosting the application on a platform like Heroku or AWS for accessibility.

#Dataset Information
The dataset contains patient health records, including:

Age
Gender
Chest Pain Type
Resting Blood Pressure
Cholesterol Levels
Fasting Blood Sugar
Resting ECG Results
Max Heart Rate Achieved
Exercise-Induced Angina
Old Peak (ST depression induced by exercise)
Slope of the ST Segment
Number of Major Vessels Colored by Fluoroscopy
Thalassemia
The target variable indicates whether the patient has heart disease (binary classification: 1 = presence, 0 = absence).

#Technologies Used
Programming Language: Python
Libraries:
Data Analysis: Pandas, NumPy
Visualization: Matplotlib, Seaborn
Machine Learning: Scikit-learn, TensorFlow, XGBoost
Deployment: Flask, Streamlit
Notebook Environment: Jupyter Notebook

#Project Workflow
Data Import and Initial Analysis
Understanding the dataset structure and identifying issues.
Data Cleaning
Handling missing and noisy data.
Feature scaling and encoding.

#EDA
Visualizing distributions and correlations to derive meaningful insights.
Model Training
Splitting data into training and test sets.
Training multiple algorithms and fine-tuning parameters.
Model Evaluation
Selecting the best-performing model based on evaluation metrics.
Deployment
Packaging the model into an accessible application or API.
Results
The best-performing model achieves:

Accuracy: 96%
Precision: 97%
Recall: 95%
ROC-AUC Score: 96%
These results indicate the model’s ability to predict heart disease effectively.

