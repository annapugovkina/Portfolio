# Проект по работе с клиентами оператора связи: модель прогноза оттока клиентов
[ссылка на проект в ipynb](https://github.com/annapugovkina/Portfolio/blob/main/Telecom/Customer_churn_Telecom.ipynb)

## Описание проекта
Оператору связи необходимо предложить одну или несколько моделей, прогнозирующих отток клиентов, для целей предложения промо акций и удержания клиентов. В рамках решения этой задачи необходимо также провести исследовательский анализ данных, выявить закономерности и предположить причины ухода клиентов. Дополнительно предложить решения по снижению оттока клиентов. 

Задача классификации (клиент уйдет или останется, 1 и 0), в качестве метрики качества выбрана roc_auc > 0.85.

## Навыки и инструменты

- python
- pandas
- skimpy.clean_columns
- numpy
- matplotlib
- seaborn
- phik
- sklearn.model_selection.GridSearchCV
- sklearn.preprocessing.OrdinalEncoder, OneHotEncoder, StandardScaler
- sklearn.linear_model.LogisticRegression
- sklearn.ensemble.RandomForestClassifier
- catboost.CatBoostClassifier
- lightgbm.LGBMClassifier
- sklearn.metrics.accuracy_score, confusion_matrix, roc_curve, roc_auc_score

## Общий вывод
В проекте решалась задача классификации. Было выбрано четыре модели для обучения (две простые модели и две бустинговые), проведена проверка на тестовой выборке и выбрана одна модель как наиболее оптимальная по метрике roc-auc (в связи с дисбалансом классов).

