# House Price Prediction using Machine Learning

## 📌 Project Overview

House price prediction is an important application of Machine Learning that helps buyers, sellers, and real estate investors estimate property prices based on different housing features. This project builds a regression model to predict house prices using demographic, geographic, and housing-related information.

The project follows a complete end-to-end Machine Learning workflow, including data preprocessing, feature engineering, model building, model evaluation, and comparison.

---

## 🎯 Project Objective

- Predict house prices using Machine Learning regression algorithms.
- Analyze the factors that influence house prices.
- Compare multiple regression models to identify the best-performing model.
- Understand the importance of feature engineering in improving model performance.

---

## 📂 Dataset Information

The dataset contains information about houses, including:

- Longitude
- Latitude
- Housing Median Age
- Total Rooms
- Total Bedrooms
- Population
- Households
- Median Income
- Ocean Proximity
- Median House Value (Target Variable)

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
9. Train-Test Split
10. Feature Scaling
11. Model Building
12. Model Evaluation
13. Model Comparison
14. Final Conclusion

---

## ⭐ Feature Engineering

To improve the predictive performance of the models, the following new features were created:

- **rooms_per_household** = Total Rooms / Households
- **bedrooms_per_room** = Total Bedrooms / Total Rooms
- **population_per_household** = Population / Households

These engineered features helped the models learn meaningful relationships within the data and improved prediction accuracy.

---

## ⚙️ Machine Learning Models Used

- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor

---

## 📈 Model Performance

| Model | MAE | MSE | R² Score |
|--------|------------:|------------:|---------:|
| Linear Regression | 49,665.19 | 4.86 × 10⁹ | 0.6367 |
| Decision Tree Regressor | 43,861.60 | 4.57 × 10⁹ | 0.6400 |
| Random Forest Regressor | **32,478.92** | **2.50 × 10⁹** | **0.8114** |

🏆 **Best Performing Model:** Random Forest Regressor

---

## 📌 Key Results

- Successfully predicted house prices using Machine Learning.
- Performed data cleaning and preprocessing.
- Applied Feature Engineering to improve prediction performance.
- Compared multiple regression algorithms.
- Random Forest Regressor achieved the best performance with an **R² Score of 0.8114**.
- The model explained approximately **81%** of the variance in house prices.

---

## 🔍 Key Insights

The most important observations from the project include:

- Median Income is one of the strongest predictors of house prices.
- Ocean Proximity significantly influences property values.
- Feature Engineering improved the model's predictive performance.
- Random Forest captured complex relationships better than Linear Regression and Decision Tree.

---

## 🚀 Future Improvements

- Perform Hyperparameter Tuning to further improve model performance.
- Experiment with advanced ensemble models such as XGBoost.
- Deploy the trained model using Streamlit or Flask.
- Train the model on larger and more diverse real-world housing datasets.

---

## 🎯 Conclusion

This project demonstrates a complete Machine Learning workflow for house price prediction. It includes data preprocessing, feature engineering, regression model development, model evaluation, and comparison.

Among all the models, **Random Forest Regressor** achieved the best performance with an **R² Score of 0.8114**, making it the most suitable model for predicting house prices in this dataset.

---

## 👨‍💻 Author

**Shashi Bala**

If you found this project useful, feel free to ⭐ this repository.
