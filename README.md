# **Bike Sharing Demand Prediction – Linear Regression Model** 

## **Project Overview**
This project aims to predict bike-sharing demand for a bike rental service using a **Linear Regression Model**. The objective is to analyze key factors affecting demand and provide data-driven insights to optimize resource allocation, manage supply efficiently, and enhance customer satisfaction.

## **Dataset & Preprocessing**
- The dataset contains various factors influencing bike demand, including weather conditions, holiday status, and seasonal trends.
- Key preprocessing steps include:
  - Handling missing values and outliers.
  - Feature engineering to create meaningful predictors.
  - Scaling numerical variables for better model performance.

## **Model Building & Performance**
A **Linear Regression Model** was implemented to predict bike demand. The model performance was evaluated using key metrics:
- **R² Score**: Measures how well the model explains variation in demand.
- **RMSE (Root Mean Squared Error)**: Assesses prediction accuracy.
- **Adjusted R²**: Ensures model generalizability by accounting for unnecessary predictors.

## **Key Findings & Recommendations**
1. **Weather & Seasonal Impact**: The model indicates a strong correlation between weather conditions and bike demand. Poor weather significantly reduces rentals.
2. **Time-Based Trends**: The number of rentals fluctuates based on holidays and peak commuting hours. Implementing dynamic pricing during peak times could optimize revenue.
3. **Feature Importance**: Factors such as temperature and working days play a crucial role in predicting demand. Adjusting fleet availability accordingly can improve efficiency.

## **Repository Structure**
The repository contains the following files:
- **Solution - Linear Regression Model - Linh Pham.ipynb**: The Jupyter Notebook with data preprocessing, model building, and evaluation.
- **README.md**: A detailed description of the project and instructions.
- **day.csv**: raw dataset for model building