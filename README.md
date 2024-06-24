# sales-forecasting

Sales Forecasting Project with ARIMA & LSTM

- Dataset Description
- Dataset Size: 6736 data points
- Source: STORE ECUADOR
- Categories (FAMILY): Automotive, Beauty, Beverages, Bread/Bakery

Analysis
- AUTOMOTIVE Category:
Both ARIMA and LSTM models show similar RMSE values on the test set, with ARIMA slightly outperforming LSTM in accuracy.
- BEAUTY Category:
ARIMA and LSTM models again show comparable RMSE values, with LSTM performing slightly better in accuracy.
- BEVERAGES Category:
LSTM significantly outperforms ARIMA in terms of RMSE values on both training and test sets, and also achieves higher accuracy.
- BREAD/BAKERY Category:
LSTM shows lower RMSE values compared to ARIMA on both training and test sets, and achieves a slightly higher accuracy.

Conclusion
- Model Performance: In most categories, LSTM shows promising results with lower RMSE values and comparable or higher accuracy compared to ARIMA.
- Considerations: The choice between ARIMA and LSTM may vary depending on the specific characteristics of the data and the forecasting requirements.
- This comparison highlights the effectiveness of LSTM models in capturing complex patterns and dependencies in time series data, often leading to improved forecasting accuracy compared to traditional ARIMA models.
