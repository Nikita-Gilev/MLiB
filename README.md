# MLiB
курсовой проект ML в бизнесе

Итоговый проект курса "Машинное обучение в бизнесе"

ML: sklearn, pandas, numpy API: flask Данные с kaggle - https://www.kaggle.com/pinakimishrads/fake-news-classifier-data

Задача: предсказать по опубликовано тексту является ли он обманом или нет (поле label). Бинарная классификация

Используемые признаки:
title
text

Преобразования признаков: tfidf

Модель: GradientBoostingClassifier

Описание шагов
- Step_1 - загрузка данных, сбор Pipeline и обучение модели;
- Step_2 - проверка работоспособности и нашего Pipeline;
- Шаг_3 запрос- Запрос к сервису;
- Шаг 3 построение сервера - наш сервис, который запускаем
