# stock-price-forecasting-arima-prophet
Forecasting Tesla stock prices using ARIMA and Prophet time series models.

## Overview
This project forecasts Tesla stock prices using historical market data. Two forecasting models, ARIMA and Prophet, are implemented and compared using multiple evaluation metrics.

## Objectives

- Analyze Tesla historical stock price data.
- Perform Exploratory Data Analysis (EDA).
- Test and achieve stationarity using differencing.
- Build ARIMA and Prophet forecasting models.
- Compare model performance using RMSE, MAE, and MAPE.
- Forecast Tesla stock prices for the next 90 days.


## Dataset
TSLA.csv

## Features
- Date
- Open
- High
- Low
- Close
- Adj Close
- Volume

**Target Variable:** Close Price

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Plotly
- Statsmodels
- Prophet
- Scikit-learn
- SciPy
- Jupyter Notebook

## Project Workflow

1. Data Loading
2. Data Cleaning & Preprocessing
3. Exploratory Data Analysis (EDA)
4. Stationarity Testing (ADF Test)
5. Differencing
6. Seasonal Decomposition
7. Train-Test Split
8. ARIMA Model Development
9. Prophet Model Development
10. Model Evaluation
11. 90-Day Future Forecast

---

## Model Performance

| Model | RMSE | MAE | MAPE |
|-------|------:|------:|------:|
| ARIMA | 199.915 | 178.517 | 50.091 |
| Prophet | 167.589 | 141.286 | 38.081 |

---

## Results

The Prophet model outperformed the ARIMA model by achieving lower RMSE, MAE, and MAPE values. It captured long-term trends and short-term fluctuations more effectively, making it the preferred model for forecasting Tesla stock prices in this project.

---

## Repository Structure

```text
tesla-stock-price-forecasting/
│
├── data/
│   └── TSLA.csv
│
├── notebooks/
│   └── Tesla_Stock_Forecasting.ipynb
│
├── reports/
│   └── Tesla_Stock_Forecasting_Report.pdf
├── README.md
├── LICENSE
└── .gitignore
```

## Future Improvements

- Implement LSTM-based forecasting.
- Explore Transformer-based time series models.
- Integrate real-time stock data APIs.
- Include news and social media sentiment analysis.
- Build an interactive forecasting dashboard.
- Extend the solution to forecast multiple stocks.

---

## Author

**Samaa Shafqat**

MS Business Analytics

SZABIST Islamabad

---

## License

This project is licensed under the MIT License.
