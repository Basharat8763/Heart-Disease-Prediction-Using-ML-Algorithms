# Heart-Disease-Prediction-Using-ML-Algorithms
## Overview
Heart disease remains one of the leading causes of mortality worldwide. Early detection plays a crucial role in improving survival rates, yet many individuals lack timely access to diagnostic services due to economic, geographical, or awareness-related barriers.  

This project focuses on building a machine learning-based predictive system capable of identifying individuals at high risk of heart disease using medical attributes such as blood pressure, cholesterol levels, ECG results, and other health indicators.  
The goal is to develop a scalable, accurate, and cost-effective system that can support healthcare professionals and improve early detection.

---

## Problem Statement
The rise in global heart-related illnesses demands efficient diagnostic methods that leverage data-driven insights. Traditional diagnosis often depends on clinical tests that may not be accessible to all individuals.  

Given a structured dataset containing features such as age, gender, blood pressure, cholesterol, ECG results, heart rate, and other medical parameters, the challenge is to:  
- Analyze these features  
- Identify patterns  
- Build an intelligent model capable of predicting heart disease risk with high accuracy  

A reliable machine learning solution can empower early intervention, reduce mortality, and make diagnostic support more accessible to underserved populations.

---

## Objectives
- Perform Exploratory Data Analysis (EDA) to study trends and patterns.  
- Conduct feature selection and preprocessing to prepare the dataset.  
- Train multiple machine learning models including Logistic Regression, Random Forest, Support Vector Machines, and others.  
- Evaluate model performance using accuracy, precision, recall, F1-score, ROC curves, and confusion matrices.  
- Select and deploy the best-performing model.  
- Provide interpretable insights to assist healthcare decision-making.

---

## Dataset Description
The dataset includes a range of medical and personal features commonly used in heart disease diagnosis. Key attributes include:

- **age**: Age of the patient  
- **gender**: Male or female  
- **chest_pain_type**: Type of chest pain experienced  
- **resting_blood_pressure**: Resting blood pressure (mm Hg)  
- **serum_cholesterol**: Cholesterol level (mg/dl)  
- **fasting_blood_sugar**: Indicator whether fasting blood sugar > 120 mg/dl  
- **resting_ecg**: Resting electrocardiographic results  
- **max_heart_rate_achieved**: Maximum recorded heart rate  
- **exercise_induced_angina**: Angina caused by exercise  
- **oldpeak**: Depression induced by exercise relative to rest  
- **slope_of_peak_exercise_st_segment**: Slope of peak exercise ST segment  
- **number_of_vessels_fluro**: Number of vessels colored by fluoroscopy  
- **thal**: Thalassemia type  
- **target**: Presence of heart disease (1 = yes, 0 = no)

---

## Tech Stack
| Category | Tools / Technologies |
|----------|----------------------|
| Programming Language | Python |
| Libraries | NumPy, Pandas, Matplotlib, Seaborn, Scikit-learn |
| IDE | Jupyter Notebook / VS Code |
| Algorithms | Logistic Regression, Random Forest, SVM, KNN, Decision Tree, Naive Bayes |
| Dataset Source | Public heart disease datasets (e.g., UCI Repository) |

---

## Project Structure
<img width="540" height="589" alt="image" src="https://github.com/user-attachments/assets/4dddde7b-3d3a-4f59-8235-fb40b7dbab5c" />


---

## Workflow
1. Load and clean dataset  
2. Perform EDA (correlation analysis, distribution plots, patterns)  
3. Apply feature selection and scaling  
4. Train multiple machine learning models  
5. Evaluate performance on test set  
6. Select best-performing model  
7. Save model and generate reports  
8. Prepare the pipeline for deployment (optional)

---

## Results
- Successful implementation of multiple ML algorithms  
- Evaluation conducted using accuracy, precision, recall, F1-score, and ROC-AUC  
- Identification of key predictors such as chest pain type, cholesterol, and oldpeak  
- Achieved strong predictive performance from models such as Random Forest and SVM  

(Note: Graphs, screenshots, and performance metrics will be added after project upload.)

---

## Future Improvements
- Build a web interface (Flask/Streamlit) for real-time predictions  
- Use advanced algorithms such as XGBoost or LightGBM  
- Apply hyperparameter tuning for improved accuracy  
- Integrate model explainability (SHAP, LIME)  
- Deploy on cloud platforms  
- Expand dataset with additional clinical features  

---

## License
This project is intended for academic and research purposes.
