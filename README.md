# 📈 Microsoft Stock - Time Series Forecasting

This project focuses on performing time series analysis on Microsoft’s stock trading data, aiming to predict the number of **Shares Traded** over time. The dataset spans from **April 1, 2015 to April 1, 2021** and includes several key stock market features.

## 🧾 Objective

To develop a time series forecasting model that can predict future trading volume based on historical patterns in Microsoft's stock market data.

## 📁 Dataset

The dataset used (`Forecasting_Project_Microsoft_Stock.csv`) includes:
- Date-wise stock prices (Open, High, Low, Close)
- Number of **Shares Traded**
- Total Turnover in INR

## 📊 Workflow

1. **Importing Data**
   - Loaded the dataset using `pandas`
   - Checked structure, types, and missing values

2. **Exploratory Data Analysis (EDA)**
   - Summary statistics of all columns
   - Uniqueness and distribution of features

3. **Preprocessing**
   - Converted `Date` to datetime format
   - Set `Date` as the index for time series operations
   - Resampling and smoothing (if applicable)

4. **Model Building**
   - Used forecasting methods such as:
     - **ARIMA / SARIMA**
     - **Exponential Smoothing (ETS)**
     - **Other time series regressors (if applied)**
   - Evaluated using standard error metrics (e.g., MAE, RMSE)

5. **Evaluation**
   - Visualized actual vs. predicted values
   - Calculated forecast accuracy and validated model assumptions

## 🛠️ Tools & Libraries

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Statsmodels, Scikit-learn (if applicable)
- Jupyter Notebook

## 📈 Sample Outputs

- Time series plots of Shares Traded
- Forecast vs. Actual comparison charts
- Residual and trend decomposition analysis

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/microsoft-stock-forecasting.git
