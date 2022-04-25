Учебный проект: 

[Прогнозирование заказов такси. Версия 1.](https://github.com/alexsurina/study-project-taxi/blob/main/taxi_1.ipynb) (train+valid+test 8 : 1 : 1, RMSE CatBoostRegressor - 38.89394)

[Прогнозирование заказов такси. Версия 2.](https://github.com/alexsurina/study-project-taxi/blob/main/taxi_2.ipynb) (train+test 9 : 1, RMSE LightGBMRegressor - 39.840184)

Инструменты: Python, pandas, numpy, matplotlib, sklearn, ML, TimeSeriesSplit, GridSearchCV, кросс-валидация, CatBoost, LightGBM, XGBoost, RandomForest, LinearRegression.  

Описание: Временные ряды. На основе исторических данных о заказах такси в аэропортах, нужно спрогнозировать количество заказов такси на следующий час. Значение метрики RMSE на тестовой выборке должно быть не больше 48. 

Проект завершен: обучены разные модели: CatBoostRegressor, LGBMRegressor, XGBoostRegressor, Случайный лес, Линейная регрессия, выполнен подбор гиперпараметров. Качество моделей проверено на тестовой выборке, все тестируемые модели дают RMSE < 48. Лучшие показатели у бустинговых моделей.


[Портфолио](https://github.com/alexsurina/Portfolio)
