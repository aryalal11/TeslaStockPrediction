# Tesla Stock Price Prediction Using Facebook Prophet

This project focuses on predicting Tesla's stock prices using **Facebook Prophet**, leveraging historical stock data from **Yahoo Finance**. The analysis emphasizes selecting and preparing relevant columns for effective time-series forecasting.

## Key Features
- **Data Collection**:  
  - Fetch Tesla's historical stock data, including open, close, high, low, volume, and date, from Yahoo Finance.

- **Preprocessing**:  
  - Select essential columns: `Date` (as the time index) and `Close` (as the target variable for prediction).  
  - Format the `Date` column and rename columns to align with Prophet's requirements (`ds` for date and `y` for target value).

- **Forecasting with Facebook Prophet**:  
  - Build and train the model on preprocessed data to predict future stock prices.  
  - Analyze trends and confidence intervals.

## Use Cases
- Provide actionable insights for investors and traders to optimize decision-making.  
- Enhance understanding of Tesla's stock price trends for financial planning.  

This project demonstrates how simple preprocessing and powerful tools like Facebook Prophet can make stock price forecasting accessible and effective.
