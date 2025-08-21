# Dominos---Predictive-Purchase-Order-System

Project Overview :
This project develops a predictive purchase order system for Domino’s by leveraging time series forecasting models (SARIMA, ARIMA, Prophet, Regression). Using historical sales and ingredient data, the system predicts weekly sales demand and generates optimized ingredient purchase orders. This minimizes wastage, stockouts, and excess costs, helping Domino’s streamline inventory and supply chain management.

Problem Statement : Domino’s needs an efficient way to forecast pizza sales and order ingredients in advance. Incorrect purchase planning leads to -
- Overstocking → Waste & higher costs
- Understocking → Stockouts & lost revenue
The solution uses historical sales data to predict demand and automatically generate a weekly purchase order for required ingredients.

Business Use Cases :
1. Inventory Management - Maintain optimal stock levels
2. Cost Reduction - Minimize wastage and over-ordering
3. Sales Forecasting - Predict weekly pizza demand
4. Supply Chain Optimization - Align ordering with demand trends

Approach :
1. Data Preprocessing & Cleaning
   - Handle missing values, outliers, and formatting
   - Standardize datasets (Sales + Ingredients)

2. Exploratory Data Analysis (EDA)
   - Identify sales trends, seasonality & demand patterns
   - Visualize correlations between sales and external factors

3. Sales Forecasting
   - Models: ARIMA, SARIMA, Prophet, Linear Regression
   - Evaluation Metric: MAPE (Mean Absolute Percentage Error)
   - Best Model: SARIMA (MAPE: 18.49%)

4. Purchase Order Generation
   - Forecast sales for upcoming week
   - Map sales to ingredient requirements
   - Generate detailed purchase order sheet

Results :
1. Model Comparison
   - ARIMA MAPE: 18.94%
   - SARIMA MAPE: 18.49% (Best)
   - Prophet MAPE: 19.62%
   - Linear Regression MAPE: 19.11%
2. Final Output: Purchase order listing required ingredient quantities for the predicted sales period

Dataset :
1. Sales Data: Date, Pizza Type, Quantity Sold, Price, Category, Ingredients
2. Ingredients Data: Pizza Type, Ingredient, Quantity Needed

Tech Stack & Tools :
1. Languages: Python
2. Libraries: Pandas, Scikit-learn, Statsmodels, Matplotlib, Seaborn
3. Techniques: Data Cleaning, EDA, Time Series Forecasting, Predictive Modeling, Inventory Optimization

 Deliverables :
- Cleaned datasets
- EDA report & visualizations
- Forecasting models with evaluation metrics
- Weekly purchase order file
- GitHub repository with documented code
- Project report with findings & business impact

Technical Tags :
Python, Pandas, EDA, Time Series Forecasting, ARIMA, SARIMA, Prophet, Regression, Predictive Modeling, Inventory Management, Business Analytics


