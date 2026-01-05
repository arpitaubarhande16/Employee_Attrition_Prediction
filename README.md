# Employee Attrition Prediction using Machine Learning

## 📌 Project Overview
Employee attrition is a major challenge for organizations, leading to increased recruitment costs and loss of experienced talent. This project aims to predict whether an employee is likely to leave the organization based on various HR-related features using machine learning techniques.

The project follows a complete end-to-end data science workflow, from data loading and preprocessing to model building, evaluation, and business insights.

---

## 🎯 Objective
To build a machine learning model that can accurately predict employee attrition (Yes/No) and identify the key factors contributing to employee turnover.

---

## 📂 Dataset
- Name: IBM HR Analytics Employee Attrition Dataset  
- Source: Publicly available HR analytics dataset (Kaggle)  
- Target Variable: Attrition  
  - Yes → Employee left  
  - No → Employee stayed  

---

## 🛠 Tools & Technologies Used
- Programming Language: Python  
- IDE: Jupyter Notebook  
- Libraries:
  - Pandas
  - NumPy
  - Matplotlib
  - Seaborn
  - Scikit-learn

---

## 🔍 Project Workflow

### 1. Data Loading & Understanding
- Loaded CSV dataset using Pandas
- Checked dataset shape, data types, and missing values

### 2. Exploratory Data Analysis (EDA)
- Visualized employee attrition distribution
- Analyzed attrition with respect to:
  - OverTime
  - Job Satisfaction
  - Monthly Income
  - Years at Company

### 3. Data Preprocessing
- Converted target variable into numerical format
- Encoded categorical variables using Label Encoding
- Removed unnecessary columns
- Applied feature scaling using StandardScaler

### 4. Model Building
Implemented and compared multiple machine learning models:
- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier

### 5. Model Evaluation
- Evaluated models using:
  - Accuracy Score
  - Confusion Matrix
  - Classification Report

### 6. Feature Importance
- Identified the most important features affecting attrition using Random Forest

---

## 📊 Results
- Random Forest Classifier achieved the best performance among all models
- Key factors influencing attrition:
  - OverTime
  - Monthly Income
  - Job Satisfaction
  - Years at Company

---

## 💡 Business Insights
- Employees working overtime are more likely to leave the organization
- Low job satisfaction significantly increases attrition risk
- Higher monthly income reduces the probability of employee attrition
- The model can help HR teams take proactive steps to retain employees

---

## 🚀 Future Improvements
- Hyperparameter tuning for better model performance
- Handling class imbalance using SMOTE
- Deploying the model using Streamlit
- Adding more advanced models like XGBoost

---

## 👩‍💻 Author
Arpita Ubarhande

⭐ If you like this project, feel free to star the repository!