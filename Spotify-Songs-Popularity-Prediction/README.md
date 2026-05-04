# Spotify Songs Popularity Prediction

Проект для предсказания популярности треков Spotify с нуля реализованным Random Forest. Был написан собственный `DecisionTreeRegressor` с поддержкой числовых и категориальных признаков, реализован ансамбль `RandomForest` с bootstrap-сэмплированием и OOB-оценкой качества вместо классического train/val split. Проведён базовый feature engineering (даты, длительность, производные аудио-признаки), реализована обработка пропусков и grid search по гиперпараметрам. 

## Технологии
- NumPy
- Pandas
- Кастомная реализация Decision Tree и Random Forest
- OOB (Out-of-Bag) оценка
- Grid Search
