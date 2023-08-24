# Проект по прогнозированию заказов такси с использованием временных рядов
[ссылка на проект в ipynb](https://github.com/annapugovkina/Portfolio/blob/main/Time_series/Time_series_Taxi.ipynb)

## Описание проекта
Сервису такси необходимо спрогнозировать количество заказов такси на следующий час для целей привлечения большего количества водителей в период пиковой нагрузки. В рамках решения этой задачи необходимо также провести исследовательский анализ данных, выявить закономерности, сезонность, тренд, рассчитать скользящее среднее и скользящее стандартное отклонение.

Задача регресии, в качестве метрики качества выбрана rmse < 0.48.

## Навыки и инструменты

- python
- pandas
- numpy
- matplotlib
- scipy.stats
- statsmodels.tsa.stattools.adfuller
- statsmodels.tsa.seasonal.seasonal_decompose
- sklearn.model_selection.TimeSeriesSplit
- sklearn.model_selection.GridSearchCV
- sklearn.linear_model.LinearRegression
- sklearn.ensemble.RandomForestRegressor
- catboost.CatBoostRegressor
- sklearn.metrics.mean_squared_error

## Общий вывод
В проекте решалась задача регрессии с использованием временных рядов. Был проведен исследовательский анализ данных и выявлены закономерности, двумя способами рассчитано скользящее среднее. В рамках ML было выбрано три модели для обучения (две простые модели и одна бустинговая), проведена проверка на тестовой выборке и выбрана одна модель как наиболее оптимальная по метрике rmse.
