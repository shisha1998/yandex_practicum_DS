# Прогнозирование стоимости жилья в жилом массиве


## Данные

В наличии были следующие данные о жилье:
- широта;
- долгота;
- медианный возраст жителей жилого массива;
- общее количество комнат в домах жилого массива;
- общее количество спален в домах жилого массива;
- количество человек, которые проживают в жилом массиве;
- количество домовладений в жилом массиве;
- медианный доход жителей жилого массива;
- медианная стоимость дома в жилом массиве;
- близость к океану.

## Задача

Определить медианную стоимость квартиры.

## Используемые библиотеки
*pandas*, *numpy*, *pyspark*

## Итоги исследования

Было построено две модели линейной регрессии на разных наборах данных (используя все данные из файла или используя только числовые переменные, исключив категориальные) при помощи LinearRegression из библиотеки MLlib.

Модель линейной регрессии на всех данных показала наилучшие результаты: RMSE = 69010, MAE = 50752, R2 = 0.648.