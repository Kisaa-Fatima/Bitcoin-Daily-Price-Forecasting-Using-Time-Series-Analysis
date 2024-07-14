# Bitcoin-Daily-Price-Forecasting-Using-Time-Series-Analysis
This project involves exploring, building, and evaluating different time series forecasting models to predict the daily closing prices of Bitcoin. The models compared include Linear Regression, Polynomial Regression, and ARIMA.

# Objectives
Manipulate and prepare time series data for analysis.
Build and compare different time series forecasting models.
Evaluate and interpret the results to determine the most suitable model for forecasting Bitcoin daily prices.
# Dataset
The dataset used for this project (BTC-Daily.csv) contains daily closing prices of Bitcoin, along with dates.

#Structure
Data Exploration and Preparation

- Data Loading: Import the BTC-Daily.csv file.
- Initial Exploration: Describe the dataset, visualize the daily closing prices, and check for missing or anomalous data.
- Preprocessing: Normalize or standardize the prices if necessary.
# Building Forecasting Models

- Linear Regression: Use dates as numerical features to perform a simple linear regression.
- Polynomial Regression: Explore a non-linear model by including polynomial features.
- ARIMA Model: Test for stationarity, perform differencing if needed, determine the order of the ARIMA model, and fit the ARIMA model to the data.
# Model Evaluation and Selection

- Performance Metrics: Calculate RMSE, MAE, and MAPE for each model.
- Cross-Validation: Employ time series cross-validation techniques.
- Residual Analysis: Analyze the residuals from each model.
# Comparative Analysis and Conclusion

- Comparative Discussion: Discuss the strengths and weaknesses of each model.
- Best Model Justification: Identify the best-performing model.
- Conclusion: Summarize the findings, discussing the challenges encountered
# Conclusion
- Comparative Discussion: ARIMA model performed the best with the lowest errors compared to Linear and Polynomial Regression models.
- Challenges: Forecasting Bitcoin daily prices poses challenges due to its high volatility and non-linear nature.
- Insights: Time series models like ARIMA are more suitable for Bitcoin price forecasting.
# Future Work
Explore other non-linear models or higher-degree polynomial features.
Use additional external factors (e.g., market sentiment, trading volume) to improve the models.
