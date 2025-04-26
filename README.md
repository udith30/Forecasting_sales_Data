Forecasting Sales Data - Time series model


I applied ARIMA and SARIMA models to forecast time series data by addressing both trend and seasonal components. Using ACF and PACF plots, I identified optimal ARIMA parameters (p, d, q). To ensure stationarity, I applied first-order differencing (d=1) to eliminate trends. I fit an ARIMA(0,1,1) model to capture short-term dependencies and leveraged SARIMA to model seasonal patterns through seasonal differencing, autoregressive, and moving average components, significantly improving forecast performance.


