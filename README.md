# Task 16 – Walmart Sales Forecasting

## 📌 Objective
To forecast future weekly sales using time-series forecasting techniques.

## 📊 Dataset
Walmart Sales Forecasting Dataset (Kaggle Competition)
Records: 421,570
Columns:
- Store
- Dept
- Date
- Weekly_Sales
- IsHoliday

## 🛠 Tools Used
- Python
- Pandas
- Matplotlib
- Statsmodels
- Scikit-learn

## 🔎 Process
1. Converted Date column to datetime format.
2. Aggregated total weekly sales by date.
3. Visualized sales trend.
4. Split dataset into train (80%) and test (20%) based on time.
5. Applied Exponential Smoothing model.
6. Forecasted future sales.
7. Evaluated using MAE and MAPE.

## 📈 Model Used
Exponential Smoothing (Additive Trend + Additive Seasonality)
Seasonal Period = 52 weeks

## 📊 Evaluation Metrics
- MAE:  1824922.987780064
- MAPE:  3.9407741270743815 %

## 📁 Files Included
- task16_forecasting.ipynb
- forecast_output.csv
- forecast_report.txt
- Screenshots of plots

## 🎯 Conclusion
The model captured overall trend and seasonality.
Time-series forecasting helps in inventory planning,
revenue prediction and business strategy.
