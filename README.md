# EUA Price Forecasting using ARIMA

## Project Overview
This project focuses on forecasting the prices of **European Union Allowance (EUA) Futures** using the **ARIMA (AutoRegressive Integrated Moving Average) model**. The dataset contains daily price data from **January 1, 2010, to February 28, 2025**, and forecasts prices for the period **March 1, 2025, to March 14, 2025**. The final step involves comparing the **forecasted prices** with the **real prices** to analyze the differences.

## Data Source
The dataset is collected from **[Investing.com](https://in.investing.com/commodities/european-union-allowance-eua-year-futures-historical-data)**, which provides historical daily prices of EUA futures.

## Methodology
1. **Data Collection & Preprocessing:**
   - Import historical EUA price data.
   - Convert date column to a proper datetime format.
   - Handle missing values if necessary.
   
2. **Exploratory Data Analysis (EDA):**
   - Visualize trends, seasonality, and stationarity tests.
   - Check for autocorrelation and partial autocorrelation.

3. **ARIMA Model Implementation:**
   - Determine the optimal ARIMA(p, d, q) parameters using ACF & PACF plots.
   - Train the model on historical data.
   - Forecast EUA prices for **March 1, 2025 – March 14, 2025**.

4. **Forecast Evaluation:**
   - Collect actual prices for the forecast period.
   - Compare forecasted vs. real prices.
   - Compute errors (MAE, RMSE) and analyze deviations.

5. **Visualization & Interpretation:**
   - Plot forecasted vs. real prices.
   - Highlight trends and possible reasons for deviations.

## Dependencies
Ensure you have the following Python libraries installed:
```bash
pip install pandas numpy matplotlib seaborn statsmodels
```

## Usage
Run the script using:
```bash
python eua_price_forecasting.py
```

## Results
- Forecasted prices from **March 1, 2025, to March 14, 2025**.
- Comparison with real prices to assess prediction accuracy.
- Insights on EUA price trends and factors affecting deviations.

## Conclusion
This project provides a **data-driven approach** to forecast EUA prices using ARIMA and evaluates the accuracy by comparing with real prices. It helps in understanding **market trends, volatility, and forecasting reliability**.

## Author
**Nikita Verma**

---
Feel free to contribute or suggest improvements!

