# Corporate Stress Level Prediction Using Machine Learning

This project aims to predict stress levels among corporate employees using machine learning techniques. It utilizes a dataset sourced from Kaggle that captures various personal and professional attributes related to workplace stress. The goal is to support HR analytics and employee well-being initiatives through early identification of stress patterns.

---

## Dataset Overview

The dataset contains 30 columns representing employee information and workplace factors, including:

- **Demographics:** `Age`, `Gender`, `Marital_Status`, `Location`
- **Job Details:** `Job_Role`, `Experience_Years`, `Monthly_Salary_INR`, `Working_Hours_per_Week`, `Remote_Work`, `Company_Size`, `Department`, `Team_Size`
- **Lifestyle & Health:** `Commute_Time_Hours`, `Sleep_Hours`, `Physical_Activity_Hours_per_Week`, `Health_Issues`, `Burnout_Symptoms`
- **Support & Satisfaction:** `Manager_Support_Level`, `Family_Support_Level`, `Work_Pressure_Level`, `Job_Satisfaction`, `Work_Life_Balance`, `Performance_Rating`, `Training_Opportunities`
- **Other Indicators:** `Mental_Health_Leave_Taken`, `Annual_Leaves_Taken`, `Gender_Bias_Experienced`, `Discrimination_Experienced`
- **Target Variable:** `Stress_Level`

---

## Project Workflow

1. **Data Preprocessing**
   - Handling missing values
   - Encoding categorical variables
   - Normalizing numerical features

2. **Exploratory Data Analysis (EDA)**
   - Visualizations for stress trends
   - Correlation heatmaps
   - Feature distributions and insights

3. **Model Building**
   - Train/test split
   - Algorithms: Logistic Regression, Random Forest, SVM, XGBoost
   - Hyperparameter tuning (GridSearchCV)

4. **Model Evaluation**
   - Metrics: Accuracy, Precision, Recall, F1-Score, ROC-AUC
   - Confusion matrix
   - Feature importance analysis

---

##  Sample Insights

- Stress is correlated with long commute hours, poor manager support, and low work-life balance.
- Remote workers tend to have slightly lower average stress.
- Burnout symptoms and sleep hours show strong predictive power.
