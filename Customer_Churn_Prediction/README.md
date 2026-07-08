# Customer Churn Prediction using Machine Learning

## 📌 Project Overview

Customer churn is one of the biggest challenges for businesses because losing existing customers can directly impact revenue and growth. The goal of this project is to build a Machine Learning model that predicts whether a customer is likely to leave (churn) or stay with the company.

This project follows a complete end-to-end Machine Learning workflow, including data preprocessing, exploratory data analysis (EDA), feature engineering, model building, hyperparameter tuning, and feature importance analysis.

---

## 🎯 Project Objective

- Predict customer churn using Machine Learning classification algorithms.
- Identify the key factors that influence customer churn.
- Compare multiple models to find the best-performing model.
- Understand the impact of feature engineering and hyperparameter tuning on model performance.

---

## 📂 Dataset Information

The dataset contains customer information such as:

- Customer demographics
- Services subscribed
- Contract details
- Payment methods
- Monthly charges
- Total charges
- Customer tenure
- Churn status (Target Variable)

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 📊 Project Workflow

1. Project Objective
2. Import Libraries
3. Load Dataset
4. Dataset Overview
5. Data Cleaning
6. Exploratory Data Analysis (EDA)
7. Feature Engineering
8. Data Preprocessing
9. Feature Selection
10. Train-Test Split
11. Feature Scaling
12. Model Building
13. Model Evaluation
14. Hyperparameter Tuning
15. Model Comparison
16. Feature Importance Analysis
17. Final Conclusion

---

## ⚙️ Machine Learning Models Used

- Logistic Regression
- Decision Tree
- Random Forest
- Tuned Random Forest (GridSearchCV)

---

## 📈 Model Performance

| Model | Accuracy | Precision | Recall | F1 Score |
|--------|---------:|----------:|--------:|---------:|
| Logistic Regression | **79.32%** | 62.85% | **54.28%** | **58.25%** |
| Decision Tree | 72.42% | 48.31% | 53.48% | 50.76% |
| Random Forest | 78.68% | 62.50% | 49.47% | 55.22% |
| Tuned Random Forest | 79.03% | **63.57%** | 49.47% | 55.64% |

🏆 **Best Performing Model:** Logistic Regression

---

## ⭐ Feature Engineering

To improve the model, two new features were created:

- **TotalServices** – Represents the total number of services used by each customer.
- **TenureGroup** – Groups customers based on their tenure.

These engineered features appeared among the top important features, showing that they added useful information to the model.

---

## 📊 Top Important Features

Feature Importance Analysis showed that the following features had the greatest impact on predicting customer churn:

1. Tenure
2. Contract
3. TotalCharges
4. MonthlyCharges
5. OnlineSecurity
6. TechSupport
7. InternetService
8. PaymentMethod
9. TenureGroup
10. TotalServices

---

## 📌 Key Results

- Successfully predicted customer churn using Machine Learning.
- Performed Exploratory Data Analysis (EDA) to understand customer behavior.
- Applied Feature Engineering to create meaningful new features.
- Compared multiple classification algorithms.
- Improved the Random Forest model using Hyperparameter Tuning (GridSearchCV).
- Logistic Regression achieved the best overall performance with **79.32% accuracy**.

---

## 🚀 Future Improvements

- Handle class imbalance using techniques such as SMOTE or `class_weight='balanced'`.
- Perform advanced feature engineering.
- Experiment with advanced models such as XGBoost or LightGBM.
- Deploy the trained model using Streamlit or Flask.

---

## 🎯 Conclusion

This project demonstrates a complete Machine Learning workflow for customer churn prediction. It covers data cleaning, exploratory data analysis, feature engineering, preprocessing, model building, evaluation, hyperparameter tuning, and feature importance analysis.

Among all the models, **Logistic Regression** achieved the best overall performance with an accuracy of **79.32%**. The project also highlights the importance of comparing different models and understanding the factors that influence customer churn.

---

## 👨‍💻 Author

**Kashish Chauhan**

If you found this project useful, feel free to ⭐ this repository.
