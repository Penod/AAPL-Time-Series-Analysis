# 📈 Time Series Analysis of Apple Stock (AAPL)

This project performs a comprehensive time series analysis on the closing prices of Apple Inc. (AAPL) stock. It explores underlying patterns such as trend and seasonality, assesses stationarity, and builds forecasting models using **ARIMA** and **ETS** techniques. The goal is to identify the most accurate model for forecasting future stock movements and interpret the results using statistical diagnostics and confidence intervals.

---

## 🔍 Key Features

- Real-world financial time series data
- Exploratory data analysis & visualization
- Time series decomposition (trend, seasonal, residual)
- Stationarity check using Augmented Dickey-Fuller test
- Model fitting with `auto.arima()` and `ets()`
- Residual diagnostics for model validation
- Forecasting with 80% and 95% confidence intervals
- Model comparison using AIC and RMSE

---

## 📊 Forecast Preview

![Forecast Plot](path_to_your_forecast_plot_image.png)

---

## 📁 Files

| File Name                              | Description                              |
|----------------------------------------|------------------------------------------|
| `aapl_time_series_analysis.Rmd`        | Main R Markdown file for full analysis   |
| `AAPL.csv`                             | Historical daily closing price data      |
| `forecast_plot.png` *(optional)*       | Output plot for visualization            |

---

## 📦 R Packages Used

- `tidyverse`
- `forecast`
- `tseries`
- `lubridate`
- `knitr`

---

## 🧪 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/aapl-time-series.git
   cd aapl-time-series
