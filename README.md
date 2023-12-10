# Определение стоимости автомобилей

[ipynb](https://github.com/Nanzhik/Predict-of-car-price/blob/main/Predict-of-car-price.ipynb)

## Описание проекта

Необходимо построить модель для определения рыночной стоимости автомобиля по историческим данным (технические характеристики, комплектации и цены автомобилей) для сервиса по продаже автомобилей с пробегом, которое разрабатывает приложение для привлечения новых клиентов

## Навыки и инструменты

* **python**
* **pandas**
* **numpy**
* **seaborn**
* matplotlib.**pyplot**
* phik.report.**plot_correlation_matrix**
* sklearn.linear_model.**LinearRegression**
* sklearn.ensemble.**RandomForestRegressor**
* lightgbm.**LGBMRegressor**
* xgboost.**XGBRegressor**
* catboost.**CatBoostRegressor**

## Вывод

- Изучена общая информация об исходных данных, проведена предобработка данных;
- На основе предобработанных данных произведено разделение выборок. Данные кодировали при помощи двух методов: *OneHotEncoder* и *OrdinalEncoder*.
- Обучили и сравнили показатели пяти моделей: *LinearRegression*, *RandomForestRegressor*, *CatBoostRegressor*, *LGBMRegressor* и *XGBRegressor*.
- Выбрали наилучшую модель по совокупности характеристик (RMSE, время обучения и время предсказания) - *LGBMRegressor*
