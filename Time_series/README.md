# Проект по прогнозированию заказов такси с использованием временных рядов
[ссылка на проект в ipynb](https://github.com/annapugovkina/Portfolio/blob/main/Time_series/Time_series_Taxi.ipynb)

## Описание проекта
Оператору связи необходимо предложить одну или несколько моделей, прогнозирующих отток клиентов, для целей предложения промо акций и удержания клиентов. В рамках решения этой задачи необходимо также провести исследовательский анализ данных, выявить закономерности и предположить причины ухода клиентов. Дополнительно предложить решения по снижению оттока клиентов. 

Задача классификации (клиент уйдет или останется, 1 и 0), в качестве метрики качества выбрана roc_auc > 0.85.

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
В проекте решалась задача классификации. Было выбрано четыре модели для обучения (две простые модели и две бустинговые), проведена проверка на тестовой выборке и выбрана одна модель как наиболее оптимальная по метрике roc-auc (в связи с дисбалансом классов).
