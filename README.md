# Net Realization/Revenue Prediction Model

## Overview

This project involves building a **Net Realization (Revenue) Prediction model** using **Random Forest Regression**. The aim is to predict the net realization (revenue per ton) based on various input features, including market indicators, freight rates, and product specifications. The data was sourced from multiple channels, including market data on commodities, customer details, and transaction-specific information.

## Project Details

- **Client**: [Confidential]
- **Model Type**: Random Forest Regressor
- **Key Objective**: Predict **Net Realization (NR)** using market, product, and customer-specific data.
- **Data Sources**: Multiple sources, including:
  - Market data (iron ore prices, pig iron costs)
  - Product specifications (diameter, class)
  - Customer details (customer groups, payment terms)

### Features Used

- **Iron Ore Prices**: Historical prices of iron ore.
- **Pig Iron FG**: Cost per ton of pig iron.
- **Freight Rates**: Transportation costs per meter.
- **Market Indicators**: Monthly Premium HCC, WPI, etc.
- **Customer Group**: Categories of customers (B2B, B2E, B2G).
- **Product Specifications**: Diameter and class of products.

## Workflow

1. **Data Cleaning & Preprocessing**:
   - Handled missing values and performed transformations on the dataset.
   - Applied feature engineering techniques, such as categorizing customer groups and normalizing product specifications.

2. **Exploratory Data Analysis (EDA)**:
   - Conducted correlation analysis and data visualization to identify relationships between variables.
   - Used visualizations like heatmaps and boxplots to gain insights into data trends.

3. **Modeling**:
   - Implemented **Random Forest Regression** using scikit-learn.
   - Split the dataset into training (70%) and test (30%) sets.
   - Evaluated the model using **Mean Absolute Percentage Error (MAPE)** and accuracy metrics.

4. **Model Evaluation**:
   - Key features impacting revenue were identified through feature importance analysis.
   - The model's accuracy and MAPE are reported to gauge performance.

## Results

- **Feature Importance**: The most significant predictors of revenue included freight rates, pig iron costs, and market indicators.
- **Accuracy**: The model achieved a Mean Absolute Percentage Error (MAPE) of **X%**.

## Visualizations

- **Feature Importance Plot**: Highlighted the top 20 important features.
- **Market Trend Visualizations**: Time series plots for iron ore prices and coke CFR India prices.

## Files in Repository

- `OCS Analysis - Colab.ipynb`: Contains code for data processing, model training, and evaluation.
