# Телеком | Прогноз оттока клиентов

[![made-with-python](https://img.shields.io/badge/Made%20with-Python-1f425f.svg)](https://www.python.org/)

<div style="display: flex;">
    <p style="background-color: #873276; border-radius: 3px; padding: 1px 5px; margin-right: 5px; font-size: 12px; font-weight: 500">
        Анализ данных
    </p>
    <p style="background-color: #299910; border-radius: 3px; padding: 1px 5px; margin-right: 5px; font-size: 12px; font-weight: 500">
        Машинное обучение
    </p>
    <p style="background-color: #346792; border-radius: 3px; padding: 1px 5px; font-size: 12px; font-weight: 500;">
        PostgreSQL
    </p>
</div>

<br>

Свойство | Значение
-|-
Источник данных | Данные предоставлены заказчиком
Расположение данных | База данных PostgreSQL
Характер данных | Персональные данные о некоторых клиентах, информация об их тарифах и услугах
Концепт исследования | Предупреждение оттока клиентов за счёт предложения промокодов и специальных условий всем, кто планирует отказаться от услуг связи
Задача исследования | Построить модель, которая будет предсказывать, разорвёт ли абонент договор с оператором
Условия обучения модели | Метрика ROC-AUC > 0.85