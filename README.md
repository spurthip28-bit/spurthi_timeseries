🛒 Retail Brand Sales Forecasting

This project analyzes three years of consumer purchase data (2022–2024) across multiple brands and banks to identify sales trends, seasonality, and performance drivers. Using time series forecasting (SARIMA), the project forecasts brand-level sales for the upcoming quarter and evaluates model accuracy with backtesting.

⸻

📌 Project Goals
	•	Analyze past 3 years of purchase data (sales, cardholders, active users, transactions).
	•	Explore seasonality and trends in brand performance.
	•	Evaluate drivers of sales (e.g., average purchase price, shop rate, spend rate).
	•	Build a SARIMA time series model to forecast future sales.
	•	Backtest models using MAPE, AIC, and BIC to ensure accuracy and parsimony.
	•	Provide insights for budget allocation, marketing strategy, and customer retention.

⚙️ Methodology

🔹 Exploratory Data Analysis (EDA)
	•	Distribution analysis of sales and drivers.
	•	Correlation heatmaps for identifying strong relationships.
	•	Trend analysis by month, quarter, and year.
	•	Seasonal decomposition to separate trend, seasonality, and residuals.

🔹 Time Series Modeling
	•	SARIMA (Seasonal ARIMA) selected for capturing trend + seasonality.
	•	Parameter search using grid search across (p,d,q) and (P,D,Q,s).
	•	Model evaluation using:
	•	MAPE (Mean Absolute Percentage Error) from backtesting.
	•	AIC & BIC for model parsimony.

🔹 Backtesting
	•	Rolling and block backtests performed on the last 2 quarters to compare forecasted vs actual values.
	•	Visualization of predictions with confidence intervals against real data.

🔹 Forecasting
	•	Final model forecasts next quarter’s sales (3 months).
	•	Results include point forecasts and 95% confidence intervals.

📊 Key Visuals
	•	Sales seasonality heatmaps.
	•	Correlation heatmaps (sales vs drivers).
	•	ACF/PACF plots for lag identification.
	•	Backtesting plots (actual vs forecast).
	•	Final sales forecast with 95% confidence bands.

🛠️ Tech Stack
	•	Python: pandas, numpy, matplotlib, seaborn, statsmodels, scikit-learn
	•	Jupyter Notebook / Google Colab for experimentation
	•	SARIMAX for forecasting

