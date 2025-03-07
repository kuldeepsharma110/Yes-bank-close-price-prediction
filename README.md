# Yes-bank-close-price-prediction
Prediction of Yes bank close price based on historical OHLC data.

![image](https://github.com/user-attachments/assets/3ab01bb9-f8e7-409c-bb9f-d9ed652ad34e)


## Overview
Yes Bank is a well-known bank in the Indian financial domain. Since 2018, it has been in the news because of the fraud case involving Rana Kapoor. Owing to this fact, it was interesting to see how that impacted the stock prices of the company and whether Time series models or any other predictive models can do justice to such situations. This dataset has monthly stock prices of the bank since its inception and includes closing, starting, highest, and lowest stock prices of every month. The main objective is to predict the stock’s closing price of the month.

## Data Description
* It consists of 5 columns
  
| Field | Description |
|-------|-------------|
| Date  | Date of record |
| Open  | Opening price of the day |
| High  | Highest price of the day |
| Low   | Lowest price of the day |
| Close | Closing price of the day |

## Conclusion
In this project, we aimed to predict the closing price of Yes Bank using machine learning techniques and hyperparameter optimization.

* Hyperparameter Optimization: We used GridSearchCV for hyperparameter tuning since our dataset was small, allowing an exhaustive search of all parameter combinations to ensure the best selection.
* Performance Improvement: After tuning, the Mean Squared Error (MSE) significantly improved from 0.8922 to 0.0048, indicating a substantial enhancement in model accuracy.
* Evaluation Metric: MSE (Mean Squared Error) was chosen as the primary evaluation metric because it effectively measures prediction error, helping the business identify the best model for accurate price forecasting.
* Final Model Selection: Ridge Regression with GridSearchCV was chosen as the final model due to its high prediction accuracy and the lowest MSE (0.00479), making it the best fit for the task.

## Tools and skills used
* Python
* Sklearn
* regression analysis
* Evaluation matrix
* Predictive modelling

