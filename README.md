# Real-Time Heart Disease Prediction

# Project Overview
- This project aims to predict the 10-year risk of future coronary heart disease (CHD) in patients based on various health indicators.
- The model is trained on data from the Framingham Heart Study.

# Dataset Overview
- The dataset contains over 3,700 patient records with 15 health-related features:
- Demographic: Sex (Male/Female), Age.
- Behavioral: Current smoking status and number of cigarettes per day.
- Medical History: Use of blood pressure medications, history of stroke, hypertension, and diabetes.
- Current Medical Status: Total cholesterol level, systolic and diastolic blood pressure, BMI, heart rate, and glucose levels.
- Target Variable: 10-year risk of coronary heart disease (TenYearCHD).

# Methodology
- Data Preprocessing: Handled missing values and dropped irrelevant columns (e.g., education).
- Feature Engineering: Renamed columns for clarity and scaled data for model readiness
- Model Selection: A Decision Tree algorithm was implemented to classify patient risk.
- Evaluation: The model was evaluated using a classification report, accuracy score, and confusion matrix.

# Machine Learning Models Used
- Random Forest
- Logistic Regression
- Support Vector Machine (SVM)
- Decision Tree
- Naive Bayes (Gaussian)

# Technologies & Tools
- Python
- Scikit-learn
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
 
# Results
- The Random Forest model achieved the following performance metrics:
- Accuracy: Approximately 83%
- Precision (Class 0): 0.85
- Recall (Class 1): 0.96
- F1 score: 0.91



