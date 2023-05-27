# Улучшение процесса обогащения золота

[ipynb](https://github.com/NickMesch/Practicum/blob/main/Gold%20recovery/Gold_recovery.ipynb)

## Описание проекта

Подготовьте прототип модели машинного обучения.

Модель должна предсказать коэффициент восстановления золота из золотосодержащей руды. Используйте данные с параметрами добычи и очистки.

Итоговая метрика качества sMAPE для дух этапов обработки - грубой и финальной в соотношении 25% и 75%



## Навыки и инструменты

- **python**
- **pandas**
- **numpy**
- **scipy**
- **matplotlib**
- sklearn.model_selection.**cross_val_score**
- sklearn.metrics.**mean_absolute_error, make_scorer, mean_absolute_percentage_error**
- sklearn.linear_model.**LinearRegression, Lasso**
- sklearn.tree.**DecisionTreeRegressor**
- sklearn.ensemble.**RandomForestRegressor**
- sklearn.dummy.**DummyRegressor**


## 

## Вывод

Были выбраны значимые признаки, проведено обучение моделей для стадий грубой и финальной очистки, произведена проверка обученных моделей на тестовых данных и выбрана оптимальная для запуска в производство.
