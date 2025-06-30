# Heart-Disease-Prediction-Using-ML-Algorithms
Problem Statement
The increasing prevalence of heart diseases, a leading cause of mortality globally, necessitates effective measures for early detection and prevention. Despite significant advancements in medical science, many individuals remain deprived of timely diagnoses due to economic limitations, lack of awareness, or inadequate access to healthcare services. This disparity underlines the critical need for scalable and affordable diagnostic solutions. Given a dataset comprising features such as age, gender, blood pressure, cholesterol levels, blood sugar levels, and other relevant medical parameters, this study seeks to address the challenge of predicting heart disease risk. The problem lies in accurately analyzing these features to identify high-risk individuals and develop a machine learning-based predictive model. Such a solution would enable proactive interventions, reduce mortality rates, and make early heart disease detection accessible to underserved populations.

Objective
The primary aim of this study is to leverage machine learning algorithms to develop a predictive model for heart disease. Specifically, the objectives include:

1. Exploratory Data Analysis (EDA): Analyze and visualize the dataset to identify key patterns and trends.
2. Feature Engineering: Select and preprocess the most relevant features that influence heart disease.
3. Model Development: Implement various machine learning algorithms to predict heart disease with high accuracy.
4. Performance Evaluation: Compare model performances using metrics such as accuracy, precision, recall, and F1-score to identify the most effective algorithm.
5. Insights and Recommendations: Provide actionable insights to healthcare professionals and individuals for better risk assessment and prevention strategies.

Data Description
The dataset used in this project contains various features related to heart disease prediction. It comprises medical attributes and personal details of individuals, which will be used to predict the likelihood of heart disease. The detailed data dictionary is provided below.

age: Age of the individual (in years)
gender: Gender of the individual (male or female)
chest_pain_type: Type of chest pain (e.g., typical angina, atypical angina, non-anginal pain, asymptomatic)
resting_blood_pressure: Resting blood pressure (in mm Hg)
serum_cholesterol: Serum cholesterol level (in mg/dl)
fasting_blood_sugar: Fasting blood sugar (1 if greater than 120 mg/dl, 0 if less than or equal to 120 mg/dl)
resting_ecg: Resting electrocardiographic results (values range from 0 to 2 indicating different types of results)
max_heart_rate_achieved: Maximum heart rate achieved during stress testing (in beats per minute)
exercise_induced_angina: Exercise-induced angina (1 if present, 0 if not)
oldpeak: Depression induced by exercise relative to rest (a measure of ST depression)
slope_of_peak_exercise_st_segment: The slope of the peak exercise ST segment (e.g., up, flat, down)
number_of_vessels_fluro: Number of vessels colored by fluoroscopy (ranges from 0 to 3)
thal: Thalassemia type (1 = normal, 2 = fixed defect, 3 = reversable defect)
target: Target variable indicating whether the individual has heart disease (1 = present, 0 = absent)
