# Insurance Cost Prediction

## Project Overview

This project focuses on predicting insurance costs using various machine learning models. The dataset contains information about individuals, including their age, sex, BMI, number of children, smoking status, and region. The goal is to build and evaluate different regression models to predict insurance charges based on these features.

## Dataset

The dataset used in this project is the [Insurance Dataset](https://www.kaggle.com/datasets/mirichoi0218/insurance). It includes the following columns:

- **age**: Age of the individual
- **sex**: Gender of the individual (male or female)
- **bmi**: Body mass index
- **children**: Number of children/dependents
- **smoker**: Whether the individual is a smoker (yes or no)
- **region**: The region where the individual lives (southeast, southwest, northwest, northeast)
- **charges**: The insurance charges for the individual

## Data Preprocessing

1. **Data Loading**: The data is loaded from a CSV file using `pandas`.
2. **Exploratory Data Analysis (EDA)**: Various visualizations and statistical summaries are used to understand the data.
3. **Encoding**: Categorical variables (`sex`, `smoker`, `region`) are encoded into numerical values using `LabelEncoder`.
4. **Splitting Data**: The data is split into training and testing sets using `train_test_split`.

## Models Used

1. **Linear Regression**
2. **Ridge Regression**
3. **Lasso Regression**
4. **Support Vector Regression (SVR)**
5. **Decision Tree Regression**
6. **Random Forest Regression**
7. **Gradient Boosting Regression**

### Model Evaluation

The performance of the models is evaluated using metrics such as:

- **Mean Squared Error (MSE)**
- **Mean Absolute Error (MAE)**
- **R-squared Score**

Results
Linear Regression: Achieved an R-squared score of 76.03% on the test set.
Ridge Regression: Achieved an R-squared score of 76.02% on the test set.
Lasso Regression: Achieved an R-squared score of 76.03% on the test set.
SVR: Achieved an R-squared score of 84.81% on the test set.
