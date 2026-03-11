# Heart Disease Prediction using ML Algorithms

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Classification-orange)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-yellow)
![XGBoost](https://img.shields.io/badge/XGBoost-Boosting-red)

---

# Overview

Heart disease is one of the leading causes of mortality worldwide. Early detection of cardiovascular diseases can significantly improve treatment outcomes and reduce health risks.

This project presents a **machine learning-based predictive system for heart disease detection** using clinical and demographic patient data. The project involves data preprocessing, exploratory data analysis (EDA), feature analysis, and the implementation of several machine learning algorithms to determine the most effective model for predicting heart disease.

Multiple classification models were evaluated and compared using standard machine learning evaluation metrics.

This project demonstrates the practical application of **machine learning in healthcare analytics and predictive medical diagnostics.**

---

# Dataset Description

The dataset used in this project contains various clinical attributes related to heart disease prediction. These attributes represent medical measurements and personal health information used to predict whether an individual is likely to have heart disease.

### Dataset Features

- **age** – Age of the individual (in years)
- **gender** – Gender of the individual (male or female)
- **chest_pain_type** – Type of chest pain experienced
- **resting_blood_pressure** – Resting blood pressure (mm Hg)
- **serum_cholesterol** – Cholesterol level in blood (mg/dl)
- **fasting_blood_sugar** – Blood sugar level (>120 mg/dl or not)
- **resting_ecg** – Resting electrocardiographic results
- **max_heart_rate_achieved** – Maximum heart rate during exercise
- **exercise_induced_angina** – Exercise-induced angina
- **oldpeak** – ST depression induced by exercise relative to rest
- **slope_of_peak_exercise_st_segment** – Slope of peak exercise ST segment
- **number_of_vessels_fluro** – Number of vessels colored by fluoroscopy
- **thal** – Thalassemia type
- **target** – Presence of heart disease

### Target Variable
# Heart Disease Prediction using ML Algorithms

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Classification-orange)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-yellow)
![XGBoost](https://img.shields.io/badge/XGBoost-Boosting-red)

---

# Overview

Heart disease is one of the leading causes of mortality worldwide. Early detection of cardiovascular diseases can significantly improve treatment outcomes and reduce health risks.

This project presents a **machine learning-based predictive system for heart disease detection** using clinical and demographic patient data. The project involves data preprocessing, exploratory data analysis (EDA), feature analysis, and the implementation of several machine learning algorithms to determine the most effective model for predicting heart disease.

Multiple classification models were evaluated and compared using standard machine learning evaluation metrics.

This project demonstrates the practical application of **machine learning in healthcare analytics and predictive medical diagnostics.**

---

# Dataset Description

The dataset used in this project contains various clinical attributes related to heart disease prediction. These attributes represent medical measurements and personal health information used to predict whether an individual is likely to have heart disease.

### Dataset Features

- **age** – Age of the individual (in years)
- **gender** – Gender of the individual (male or female)
- **chest_pain_type** – Type of chest pain experienced
- **resting_blood_pressure** – Resting blood pressure (mm Hg)
- **serum_cholesterol** – Cholesterol level in blood (mg/dl)
- **fasting_blood_sugar** – Blood sugar level (>120 mg/dl or not)
- **resting_ecg** – Resting electrocardiographic results
- **max_heart_rate_achieved** – Maximum heart rate during exercise
- **exercise_induced_angina** – Exercise-induced angina
- **oldpeak** – ST depression induced by exercise relative to rest
- **slope_of_peak_exercise_st_segment** – Slope of peak exercise ST segment
- **number_of_vessels_fluro** – Number of vessels colored by fluoroscopy
- **thal** – Thalassemia type
- **target** – Presence of heart disease

### Target Variable
0 → No Heart Disease
1 → Heart Disease Present


### Dataset Size:
303 records
14 features


---

# Project Objectives

The main objectives of this project include:

- Performing **Exploratory Data Analysis (EDA)** to understand the dataset
- Cleaning and preprocessing the data
- Identifying important features related to heart disease
- Implementing multiple **Machine Learning classification algorithms**
- Evaluating model performance using various metrics
- Comparing models to determine the **best predictive algorithm**

---

# Data Preprocessing

The dataset was preprocessed before training machine learning models.

The following steps were performed:

- Data inspection and validation
- Duplicate row removal
- Outlier detection
- Outlier treatment using **Interquartile Range (IQR) capping**
- Data splitting into training and testing datasets

After preprocessing, the dataset was clean and ready for machine learning model training.

---

# Exploratory Data Analysis (EDA)

Exploratory Data Analysis was performed to understand relationships between different features and the target variable.

Key insights from the analysis include:

- The dataset is relatively balanced between patients with and without heart disease.
- Males appear more frequently in the dataset than females.
- Certain chest pain types show stronger association with heart disease.
- Age distribution indicates that middle-aged individuals have a higher prevalence of heart disease.
- Some features such as **maximum heart rate, ST depression, and chest pain type** show stronger correlation with the target variable.

---

# Machine Learning Algorithms Implemented

The following machine learning algorithms were used to build predictive models:

- Logistic Regression
- Naive Bayes
- Support Vector Machine (SVM)
- K-Nearest Neighbors (KNN)
- Decision Tree
- Random Forest
- XGBoost

Each model was trained on the training dataset and evaluated on the testing dataset.

---

# Model Evaluation Metrics

The performance of each model was evaluated using standard classification metrics:

- Accuracy
- Precision
- Recall
- F1 Score
- AUC-ROC

These metrics provide insights into the model’s predictive ability and classification performance.

---

# Model Performance Comparison

| Algorithm | Accuracy |
|-----------|----------|
| Logistic Regression | 86.89% |
| Naive Bayes | 90.16% |
| Support Vector Machine | 86.89% |
| K-Nearest Neighbors | 62.30% |
| Decision Tree | 78.69% |
| Random Forest | **93.44%** |
| XGBoost | 80.33% |

### Best Performing Model

**Random Forest** achieved the highest performance among all algorithms.

Reasons for strong performance:

- Handles non-linear relationships effectively
- Ensemble learning reduces overfitting
- Works well with tabular medical datasets

---

# Visualizations

The project includes several visual analyses such as:

- Feature distributions
- Gender and chest pain analysis
- Correlation heatmap
- Model performance comparison
- ROC curve analysis
- Confusion matrix visualization

These visualizations help in understanding feature relationships and evaluating model performance.

---

# Project Structure

Heart-Disease-Prediction-Using-ML-Algorithms
│
├── data
│ └── heart.csv
│
├── notebook
│ └── heart_disease_prediction.ipynb
│
├── report
│ └── Heart_Disease_Prediction_Report.pdf
│
├── figures
│
├── requirements.txt
│
└── README.md


---

# Installation

Clone the repository:


git clone https://github.com/yourusername/Heart-Disease-Prediction-Using-ML-Algorithms.git


Navigate to the project directory:


cd Heart-Disease-Prediction-Using-ML-Algorithms


Install dependencies:


pip install -r requirements.txt


Run the Jupyter Notebook to reproduce the results.

---

# Conclusion

This project demonstrates the effectiveness of machine learning techniques in predicting heart disease using clinical datasets.

Among all evaluated models, **Random Forest achieved the best performance**, highlighting the strength of ensemble methods in medical prediction tasks.

Machine learning systems like this can assist healthcare professionals in **early diagnosis, risk assessment, and preventive healthcare planning.**

---

# Author

**Basharat**

Bachelor of Technology  
Computer Science and Engineering  
Sharda University
