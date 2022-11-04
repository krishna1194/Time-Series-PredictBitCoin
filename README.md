# BitCoinPrediction
I created this to learn and understand how to predict the prices of Bitcoin(BTC) using different Machine Learning models. All these files are entirely automated.

### "BitCoinPrediction - ClosingValue" Jupyter Notebook:
Extracted the Bitcoin data from cryptocmd (https://pypi.org/project/cryptocmd/) and used multiple machine learning models to understand and predict BTC.

Models tried:
  1. Simple Exponential Smoothing 
  2. Holt Winter's Exponential Smoothing 
  3. Autoregressive Integrated Moving Average (ARIMA)
  4. Seasonal Autoregressive Integrated Moving Average (SARIMA)
  5. Auto - SARIMA
  6. Prophet
  7. Prophet multivariate
  8. Bayesian regression
  9. Lasso
  10. Random forest
  11. XGBoost
  12. Lightgbm
  13. Support Vector Machines (SVM)
  14. K Nearest Neighbors (KNN)
  15. Tensorlfow LSTM
  16. DeepAR
  17. Ensemble Models

Used Grid search and Brute force method to try all different possible combinations of parameters to get the best hyperparameters.
At last used SHAP to understand the important features.


### "BitCoinPrediction - Compare" Jupyter Notebook:
This file compares how well three models (Random Forest, XGBoost, and Lasso) predict for the next 7, 15, 30, 45, 60, and 90 days. This file will help you understand how these models perform in the coming days. 
This is one way to predict time series using non-traditional time series algorithms.


### "BitCoinPrediction - Predict" Jupyter Notebook:
This file contains the code that uses XGBoost to predict the next 7, 15, 30, 45, 60, and 90 days and stores it in google drive.
