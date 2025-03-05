# Health-Failure-Clinical-record
## 📌 Project Overview

This project applies machine learning to analyze heart failure clinical records, identifying key risk factors and predicting patient outcomes. Additionally, it provides data-driven recommendations to improve patient care.

## 📂 Dataset

Source: [https://github.com/onyedika39/Health-Failure-Clinical-record/blob/main/heart_failure_clinical_records_dataset%20(1).csv]

Features: Age, sex, ejection fraction, serum creatinine, diabetes, smoking, and more

## 🎯 Objectives

Perform exploratory data analysis (EDA) to identify trends and correlations

Apply machine learning models to predict survival outcomes

Evaluate models using accuracy, precision, recall, F1-score

Provide recommendations based on key risk factors


## 🏗 Workflow

1. Data Preprocessing: Handling missing values, feature encoding, scaling


2. EDA & Visualization: Analyzing patterns using histograms, heatmaps, boxplots, pie chart


3. Feature Importance Analysis: Identifying critical features


4. Recommendations: Providing insights based on findings



## 📊 Key Findings

1. Serum Creatinine is a Strong Predictor:

Patients with elevated serum creatinine levels (>1.5 mg/dL) had a significantly higher risk of mortality. This suggests kidney dysfunction plays a crucial role in heart failure progression.



2. Ejection Fraction and Survival:

Patients with an ejection fraction below 35% had a much lower survival rate. The model identified ejection fraction as one of the most important features for prediction.



3. Age is a Significant Risk Factor:

The risk of death increased exponentially after age 60. Older patients had lower survival probabilities, making early interventions critical.



4. Impact of Smoking and Diabetes:

Smokers had a 15-20% lower survival probability compared to non-smokers.

Diabetic patients had a higher mortality risk, reinforcing the importance of diabetes management in heart failure patients.



5. Machine Learning Model Performance:

Random Forest and XGBoost performed the best, achieving an AUC-ROC score of 0.85, indicating strong predictive power.

Logistic Regression performed decently but was outperformed by ensemble models.



6. Feature Importance Analysis:

The top predictive factors identified were:

Serum Creatinine

Ejection Fraction

Age

Serum Sodium

Smoking Status




## 7. Clinical Recommendations from ML Insights:

Early monitoring of kidney function (serum creatinine levels) can improve patient outcomes.

Patients with low ejection fraction should be closely monitored and given priority for advanced treatments.

Encouraging smoking cessation and diabetes management can reduce mortality risk.




## 🔧 Technologies Used

Python, Pandas, NumPy, Matplotlib, Seaborn

Scikit-Learn, 

Jupyter Notebook 


## 📜 How to Run the Project

1. Clone the repository:

git clone : ](https://github.com/onyedika39/Health-Failure-Clinical-record-Ml)


2. Run the notebook:

jupyter notebook


3. Follow the analysis in heart_failure_analysis.ipynb.



## 📌 Future Improvements

Incorporate deep learning for improved predictions

Use real-time patient monitoring data

Deploy as a web app for clinical use

