# Прогноз количества заказов для сервиса такси

[ipynb](https://github.com/NickMesch/Practicum/blob/main/Taxi%20orders/Forecasting_taxi_orders.ipynb)

## Описание проекта

Чтобы привлекать больше водителей в период пиковой нагрузки, нужно спрогнозировать количество заказов такси на следующий час. Постройте модель для такого предсказания.

Значение метрики RMSE на тестовой выборке должно быть не больше 48.

## Навыки и инструменты

- **python**
- **pandas**
- **matplotlib**
- statsmodels.tsa.seasonal.**seasonal_decompose**
- sklearn.model_selection.**TimeSeriesSplit**
- sklearn.metrics.**mean_squared_error**
- sklearn.linear_model.**LinearRegression, Lasso**
- sklearn.ensemble.**RandomForestRegressor**
- lightgbm.**LGBMRegressor**


## 

## Выводы

- Проведено исследование трендовых и сезонных закономерностей, а так же случайной составляющей. Проведено исследование 4-х типов моделей.
- Лучшие прогнозы получены на модели LGBMRegressor с результатом по RMSE: 39.27.
- Хуже всего удается прогнозировать пики спроса (точнее - резкие изменения спроса).
