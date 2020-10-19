# Time Series Forecasting of Sales

#### by Sooyeon Won 

## Keywords 
- Analytical Framework
- Time Series Visualisation
- Comparison the results of ETS Models vs. Seasonal-ARIMA
- Model Validation
- Time Series Forecasting


## Introduction

This analysis is the project for "Time Series Forecasting" in [Udacity Predictive Analytics Nanodegree Program](https://www.udacity.com/course/predictive-analytics-for-business-nanodegree--nd008). The goal of the project is to forecast monthly sales data for a video game company, in order to help plan out the supply with demand for the company's video games Initially, I conducted the analysis using the recommended software; Alteryx. However, for this analysis, I mainly went through the same project using **python**. Though the values of the findings are not exactly matched with the outputs based on Alteryx, I could reached very similar results. 



## Summary of Findings

This analysis is mainly about forecasting for upcoming sales in a video game company. Firstly, I investigate and prepare the time series data. The provided data was appropriate to use time series models and I held out the last 4 periods of data points for validation. Then, I determined Trend, Seasonal and Error components in the data based on decomposition plots. After that, I analyse the data by applying the ARIMA and ETS models and describe the errors for both models. I compared the in-sample error measurements to both models and compare error measurements for the holdout sample in the forecast. Finally,I choose the best fitting model and forecast the next four periods.



## References

- [MASE](https://stats.stackexchange.com/questions/401759/how-can-mase-mean-absolute-scaled-error-score-value-be-interpreted-for-non-tim/415408)<br>
- [RMSE, MAE](https://machinelearningmastery.com/time-series-forecasting-performance-measures-with-python/)<br>
- [MASE](https://otexts.com/fpp2/accuracy.html)<br>
- [ETS](https://www.statsmodels.org/dev/examples/notebooks/generated/ets.html#examples-notebooks-generated-ets--page-root)<br>
- [Seasonal ARIMA reference](https://www.seanabu.com/2016/03/22/time-series-seasonal-ARIMA-model-in-python/)<br>
- [Decomposition](https://machinelearningmastery.com/decompose-time-series-data-trend-seasonality/)
