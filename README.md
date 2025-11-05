❤️ Heart Disease Prediction using Machine Learning

This project aims to predict the likelihood of heart disease in patients using multiple machine learning algorithms.
The dataset includes various medical attributes such as age, cholesterol level, blood pressure, and heart rate.
The goal is to compare different models and find the most accurate one for reliable prediction.

📂 Dataset Information

Total Records: 302

Total Features: 14

Target Variable: target (1 = Heart Disease, 0 = No Heart Disease)

Each record represents a patient’s medical profile including:

Age

Sex

Chest pain type

Resting blood pressure

Serum cholesterol

Fasting blood sugar

Rest ECG results

Maximum heart rate achieved

Exercise induced angina

Oldpeak (ST depression)

Slope of ST segment

Number of major vessels

Thalassemia type

⚙️ Steps Involved

Data Preprocessing

Handled missing values

Scaled and encoded features

Split dataset into training and testing sets

Model Building

Logistic Regression

K-Nearest Neighbors (KNN)

Random Forest Classifier

XGBoost Classifier

Used GridSearchCV for hyperparameter tuning

Model Evaluation

Accuracy

Precision, Recall, F1 Score

ROC-AUC Score


🏆 Best Performing Model

The Random Forest Classifier achieved the highest accuracy and recall, making it the most reliable model for detecting heart disease.
It efficiently handles both categorical and numerical features and provides balanced performance across all metrics.
