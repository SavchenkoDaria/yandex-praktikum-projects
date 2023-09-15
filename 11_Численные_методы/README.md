---

# 11. Построение модели определения стоимости автомобиля

---

`python` `pandas` `seaborn` `numpy` `re` `plotly` `scikit-learn` `lightgbm`

`StandardScaler` `OneHotEncoder` `OrdinalEncoder` `make_column_transformer` `make_pipeline` `mean_squared_error` `GridSearchCV` `RandomizedSearchCV` `LinearRegression` `Ridge` `Lasso` `DecisionTreeRegressor` `RandomForestRegressor` `DummyRegressor` `CatBoostRegressor` `LGBMRegressor` 

---

**Описание проекта**

Сервис по продаже автомобилей с пробегом  разрабатывает приложение для привлечения новых клиентов. В нём можно быстро узнать рыночную стоимость своего автомобиля. На основе исторические данные необходимо построить модель для определения стоимости автомобиля.

**Задачи проекта**

Разработка системы рекомендации стоимости автомобиля на основе его описания.

**Вывод**

Выполнив предобработку данных, и обучив разные модели, в том числе LGBMRegressor(), CatBoostRegressor(), лучшей моделью оказалась модель, обученная методом LGBMRegressor() со значением RMSE = 1705.3. 

---
