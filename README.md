# Проект "Прогноз оттока клиентов"

## Описание

Проект по обучению модели для прогнозирования оттока клиентов. Если выяснится, что пользователь планирует уйти, ему будут предложены промокоды и специальные условия. В нашем распоряжении персональные данные о некоторых клиентах, информация об их тарифах и договорах.

## Цель проекта

Цель этого проекта - выявить клиентов, которые собираются отказаться от услуг. Этим клиентам будут предложены промокоды и специальные условия, чтобы сохранить их.

## Методология

В процессе работы над проектом мы рассмотрели 4 таблицы с данными, провели предварительный анализ данных, подготовили данные для обучения моделей, обучили две модели (случайный лес и CatBoost), и оценили их эффективность.

## Использованные библиотеки

- pandas
- numpy
- matplotlib
- seaborn
- sklearn
- catboost

## Результаты

Бустинговая модель CatBoost показала наилучшие результаты, достигнув значения AUC-ROC 0.91 на тестовой выборке. Эта модель может быть использована для определения клиентов, которые потенциально могут уйти.

## Выводы

Проект успешно достиг своей цели – выявление клиентов, которые могут отказаться от услуг оператора. С применением алгоритмов машинного обучения, в частности, модели CatBoost, мы смогли достигнуть значительной точности в прогнозировании оттока клиентов, как показывает значение AUC-ROC в 0.91 на тестовой выборке. Это позволяет оператору связи предпринимать целенаправленные действия для удержания клиентов, включая предложение промокодов и специальных условий, что, в свою очередь, способствует повышению лояльности клиентов и снижению оттока.

Возможности для дальнейшего улучшения проекта:
Использование дополнительных данных и источников: Расширение набора данных за счёт включения дополнительной информации о поведении клиентов и их взаимодействии с сервисами может улучшить точность прогнозов.
Эксперименты с другими моделями машинного обучения: Проведение дополнительных экспериментов с различными алгоритмами может выявить ещё более эффективные подходы к прогнозированию оттока.
Анализ влияния предложенных мер на удержание клиентов: Оценка эффективности промокодов и специальных условий в контексте удержания клиентов поможет оптимизировать стратегии удержания.

Результаты этого проекта подчёркивают важность применения данных и машинного обучения для решения бизнес-задач и предоставляют мощный инструмент для улучшения клиентского сервиса и снижения оттока.

## Контакты

tg: @aferal
