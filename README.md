Forecasting Sales Data - Time series model

 I utilized ARIMA (AutoRegressive Integrated Moving Average) and SARIMA (Seasonal ARIMA) models to address both non-seasonal and seasonal components of the data. The selection was guided by examining the Autocorrelation Function (ACF) and Partial Autocorrelation Function (PACF) plots, which helped identify the appropriate order of the ARIMA model, particularly the AR (p), I (d), and MA (q) parameters. Stationarity and Differencing:

Time series data often exhibit trends or seasonality, making it non-stationary. I applied differencing techniques to remove these trends and achieve stationarity. For example, I used a first-order difference (d=1) to eliminate the trend component, transforming the series into a stationary one suitable for ARIMA modeling. This step was crucial for fitting the model effectively and ensuring accurate forecasting. Model Fitting and Optimization:

An ARIMA(0, 1, 1) model was fit, which captures the moving average component while differencing once to ensure stationarity. Additionally, the SARIMA model was employed to capture seasonal patterns by including seasonal differencing, along with seasonal autoregressive (SAR) and seasonal moving average (SMA) components.
