# 🏡 House Price Prediction Project

## 1. Problem Statement

The objective of this project is to predict house prices based on various features such as location, income level, population, and housing characteristics. Accurate house price prediction is crucial for buyers, sellers, and investors in the real estate market to make informed decisions.

---

## 2. Data Preparation

- **Initial Data Loading:** The `housing.csv` dataset was loaded into a Pandas DataFrame.
- **Categorical Feature Handling:** The `ocean_proximity` categorical feature was converted into numerical format using one-hot encoding.
- **Missing Values:** Missing values in the `total_bedrooms` column were handled by dropping the corresponding rows.
- **Feature Scaling:** Numerical features were scaled using `StandardScaler` to ensure consistent data distribution for model training.

---

## 3. Feature Engineering

To enhance the predictive power of the models, the following new features were created:

- **rooms_per_household** = `total_rooms / households`
- **bedrooms_per_room** = `total_bedrooms / total_rooms`
- **population_per_household** = `population / households`

These engineered features helped the models capture more meaningful relationships within the data, resulting in improved prediction performance.

---

## 4. Models Used

The following regression models were implemented and evaluated:

- **Linear Regression**
  - Used as the baseline regression model.

- **Decision Tree Regressor**
  - Captures complex non-linear relationships in the data.

- **Random Forest Regressor**
  - An ensemble learning algorithm that combines multiple decision trees to improve prediction accuracy and reduce overfitting.

---

## 5. Model Performance

The models were evaluated using **Mean Absolute Error (MAE)**, **Mean Squared Error (MSE)**, and **R² Score**.

| Model | MAE | MSE | R² Score |
|--------|------------:|------------:|---------:|
| Linear Regression | 49,665.19 | 4.86 × 10⁹ | 0.6367 |
| Decision Tree Regressor | 43,861.60 | 4.57 × 10⁹ | 0.6400 |
| **Random Forest Regressor** | **32,478.92** | **2.50 × 10⁹** | **0.8114** |

### Key Findings

- ✅ **Random Forest Regressor** achieved the best performance with an **R² Score of 0.8114**, explaining approximately **81%** of the variance in house prices.
- ✅ The model achieved a **Mean Absolute Error (MAE)** of approximately **$32,479**, indicating that predictions are, on average, within this range of the actual house prices.

---

## 6. Key Insights

- **Feature Engineering Matters**
  - Creating features such as `rooms_per_household`, `bedrooms_per_room`, and `population_per_household` significantly improved model performance.

- **Random Forest Performs Best**
  - The Random Forest Regressor effectively captured complex non-linear relationships and outperformed the other regression models.

- **Important Features**
  - Median income and ocean proximity remained strong predictors of house prices, while the engineered features further enhanced prediction accuracy.

---

## Conclusion

This project demonstrates a complete machine learning workflow for house price prediction, including data preprocessing, feature engineering, model building, evaluation, and comparison. The results highlight the importance of feature engineering and ensemble learning methods such as Random Forest in achieving accurate real estate price predictions.
