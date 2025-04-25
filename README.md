# 📈 Time Series Forecasting for Ad Revenue Optimization

This project focuses on optimizing **advertising revenue forecasting** using a hybrid approach combining statistical modeling and machine learning. By applying **ETS models** to non-stationary time series data and refining predictions using **XGBoost**, this solution enhances forecasting precision and supports a **data-driven dynamic reserve pricing strategy**.

---

## 🚀 Features

- ⏳ **ETS Modeling**: Forecasted ad revenue on non-stationary data using Exponential Smoothing (ETS).
- 📉 **Trend Stabilization**: Applied **first-order differencing** and validated stationarity with the **ADF test**.
- 🤖 **XGBoost Integration**: Boosted accuracy through multi-feature modeling with **XGBoost**.
- 💰 **Reserve Price Strategy**: Designed a **dynamic reserve pricing** mechanism using **25th percentile CPM segmentation** to balance revenue and market competitiveness.
- 📊 **Data-Driven Decisions**: Enabled more strategic ad auction decisions through predictive analytics.

---

## 🛠️ Tech Stack

- **Python**
- **Pandas, NumPy**
- **statsmodels** (ETS, ADF Test)
- **XGBoost**
- **Matplotlib, Seaborn** (for visualization)

---

## 💡 Methodology

1. **Exploratory Data Analysis**:
   - Analyzed seasonality, trends, and noise in ad revenue time series data.

2. **Stationarity Treatment**:
   - Applied **first differencing** to stabilize variance and trends.
   - Used **ADF Test** to validate stationarity.

3. **Forecasting**:
   - Utilized **ETS (Error, Trend, Seasonal)** model for time series prediction.
   - Enhanced with **XGBoost regression**, incorporating additional features.

4. **Dynamic Reserve Pricing**:
   - Calculated **25th percentile of CPM** (Cost Per Mille) for segmented pricing.
   - Created flexible pricing tiers based on forecasted demand and value.

---



