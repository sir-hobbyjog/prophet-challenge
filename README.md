# Forecasting with Prophet

## Project Overview
This project aims to explore the relationship between Google search trends and stock price movements, focusing on Mercado Libre as a case study. By leveraging Facebook's Prophet library, we implement a time series forecasting model to predict future stock prices based on historical data and search activity patterns.

## Purpose
The primary purpose of this analysis is to investigate whether there's a significant correlation between the volume of Google searches for a given company and its stock price movements. We delve into the intricacies of time series analysis, utilizing the Prophet library to forecast future stock price trends based on past data.

## Key Features
- Utilization of the `Prophet` library for robust time series forecasting.
- Analysis of Google search trends to predict stock market behavior.
- Exploration of volatility patterns and their implications on stock forecasts.
- Insightful visualizations to depict trends and forecast results.

## Requirements
To run this project, ensure you have the following libraries and dependencies installed:
- pandas
- Prophet
- matplotlib
- numpy

You can install these dependencies via pip:
```bash
pip install pandas prophet matplotlib numpy```  

## Additional Notes
- The analysis indicates a limited but noticeable correlation between Google search activity and stock price movements for Mercado Libre, particularly around significant corporate events like earnings releases.  
- It's essential to interpret the forecasts with caution, considering the inherent volatility in stock prices and the speculative nature of using search trends for prediction.  

## Conclusion  
While the direct causality between search trends and stock prices is complex, this project demonstrates the potential of using alternative data sources for financial forecasting. The Prophet library offers a powerful and flexible tool for time series analysis, making it accessible to both beginners and experienced analysts alike.
