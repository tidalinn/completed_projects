# Система предсказания ДТП

[![made-with-python](https://img.shields.io/badge/Made%20with-Python-1f425f.svg)](https://www.python.org/)

<br>

Свойство | Значение
-|-
**Сфера деятельности** | БДД (Безопасность Дорожного Движения)
**Тип задачи** | ML
**Источник данных** | Данные предоставлены заказчиком
**Характер данных** | Информация о происшествиях, описание участников происшествия, описание автомобиля
**Цель заказчика** | Создание системы, которая могла бы оценить риск ДТП по выбранному маршруту движения. Под риском понимается вероятность ДТП с любым повреждением транспортного средства. Как только водитель забронировал автомобиль, сел за руль и выбрал маршрут, система должна оценить уровень риска. Если уровень риска высок, водитель увидит предупреждение и рекомендации по маршруту
**Задача исследования** | Понять, возможно ли предсказывать ДТП, опираясь на исторические данные одного из регионов
**Инструменты** | Pandas, PyTorch, Scikit-learn, LightGBM, CatBoost, Skorch, SQL