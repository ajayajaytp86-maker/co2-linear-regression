CO2 Emissions Prediction using Linear Regression
1. Project Overview

This project builds a Machine Learning model to predict vehicle CO2 emissions using Linear Regression.

The objective is to:

Analyze how engine and fuel-related factors influence emission levels

Build a predictive regression model

Evaluate model performance using standard metrics

The project follows a complete machine learning workflow from data preprocessing to model evaluation.

2. Dataset
2.1 Dataset Used

CO2 Emissions Canada Dataset

2.2 Dataset Description

The dataset contains:

Vehicle specifications

Fuel consumption data

CO2 emission values

3. Selected Features
3.1 Input Variables (Independent Variables)

Engine Size (L)

Cylinders

Fuel Consumption Comb (L/100 km)

3.2 Target Variable (Dependent Variable)

CO2 Emissions (g/km)

4. Project Workflow

The project follows these steps:

Data loading and inspection

Handling missing values

Feature selection

Feature scaling using StandardScaler

Train-test split (80% training, 20% testing)

Model training using Linear Regression

Model evaluation using:

R² Score

Mean Absolute Error (MAE)

Visualization of Actual vs Predicted values

5. Model Performance

The model performance is evaluated using:

R² Score

Measures how well the model explains variance in CO2 emissions

Mean Absolute Error (MAE)

Measures the average prediction error

6. Technologies Used

Python

Pandas

Matplotlib

Scikit-learn

7. Key Learning Outcomes

Understanding regression modeling

Preventing data leakage

Feature scaling and preprocessing

Evaluating model performance

Interpreting regression coefficients

8. Conclusion

The Linear Regression model demonstrates a strong relationship between fuel consumption and CO2 emissions.

This project highlights how real-world environmental data can be analyzed and modeled using machine learning techniques.
