## Retail Store Sales Prediction using Time Series Models

This project revolves around predicting retail store sales utilizing three distinct time series forecasting models: ARIMA, SARIMA, and Prophet. The dataset comprises daily sales data spanning from December 1, 2010, to December 9, 2011, totaling 351 entries.

### Methodology
- **Data Preparation:** Integrated supplementary data sources such as holiday and temperature data, although ultimately deemed unnecessary for the prediction task.
- **Data Visualization:** Conducted comprehensive visualizations of the sales data, revealing prominent seasonal patterns inherent in the dataset.
- **Model Building (ARIMA):** Employed statistical tests including adfuller test, ACF-PACF analysis, and AIC-BIC to construct the ARIMA (AutoRegressive Integrated Moving Average) model. Despite initial optimism, plot diagnostics indicated suboptimal model performance.
- **Model Building (SARIMA):** Delved into seasonal decomposition and utilized autoarima to identify appropriate variables for the Seasonal ARIMA (SARIMA) model. However, identifying consistent seasonal patterns proved challenging, hindering model efficacy.
- **Model Building (Prophet):** Leveraged Facebook's Prophet model, a robust tool for time series forecasting. Developed a compatible dataframe and seamlessly fitted the data. The Prophet model exhibited promising forecasting capabilities, effectively capturing underlying trends and seasonality.

This project serves as a comprehensive exploration of various time series forecasting techniques, providing valuable insights into their applications and limitations.
