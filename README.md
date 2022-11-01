# Проект 3. Соревнование на Kaggle

## Оглавление
[1. Описание проекта](https://github.com/kontroler38/Project_3_Booking_review_AleksandF_v5/blob/main/README.md#Описание-проекта)

[2. Какой кейс решаем?](https://github.com/kontroler38/Project_3_Booking_review_AleksandF_v5/blob/main/README.md#Какой-кейс-решаем?)

[3. Краткая информация о данных](https://github.com/kontroler38/Project_3_Booking_review_AleksandF_v5/blob/main/README.md#Краткая-информация-о-данных)

[4. Этапы работы над проектом](https://github.com/kontroler38/Project_3_Booking_review_AleksandF_v5/blob/main/README.md#Этапы-работы-над-проектом)

[5. Результат](https://github.com/kontroler38/Project_3_Booking_review_AleksandF_v5/blob/main/README.md#Результат)

### Описание проекта
Соревнование на Kaggle (https://www.kaggle.com/competitions/sf-booking/overview)
Задача - создать модель, основанную на алгоритмах машинного обучения, которая предсказывает рейтинг отеля.

:arrow_up: [к оглавлению](https://github.com/kontroler38/Project_3_Booking_review_AleksandF_v5/blob/main/README.md#Оглавление)

### Какой кейс решаем?
Представьте, что вы работаете датасаентистом в компании Booking. Одна из проблем компании — это нечестные отели, которые накручивают себе рейтинг. Одним из способов нахождения таких отелей является построение модели, которая предсказывает рейтинг отеля. Если предсказания модели сильно отличаются от фактического результата, то, возможно, отель играет нечестно, и его стоит проверить.

**Условия соревнования:**
- Данное соревнование является бессрочным и доступно для всех потоков.
- Срок выполнения соревнования устанавливается индивидуально в каждом потоке.
- Тестовая выборка представлена в LeaderBoard целиком.
- Делаем реальный ML продукт, который потом сможет нормально работать на новых данных.

Дополнительно
Обратите внимание, что к данному соревнованию создано базовое решение

:arrow_up: [к оглавлению](https://github.com/kontroler38/Project_3_Booking_review_AleksandF_v5/blob/main/README.md#Оглавление)

**Метрика качества**
Результаты оцениваются по метрике MAPE

Файл представления
Для каждого id отеля в наборе тестовых данных вы должны предсказать рейтинг отеля для reviewer_score переменной. Файл должен содержать заголовок и иметь следующий формат:
reviewer_score, id 1,1

КРИТЕРИИ ОЦЕНИВАНИЯ:

- Качество кода (соблюдение стандартов оформления PEP-8, комментирование кода, README к проекту). Оформление проекта на GitHub, GitLab, Kaggle.
- Очистка данных.
- Исследование данных (качество визуализации, наличие идей, гипотез, комментариев).
- Генерация признаков.
- Отбор признаков.
- Преобразование признаков.
- Качество решения: результат метрики MAPE.

:arrow_up: [к оглавлению](https://github.com/kontroler38/Project_3_Booking_review_AleksandF_v5/blob/main/README.md#Оглавление)

**Что практикуем**
Главная задача — добиться максимальной точности модели

:arrow_up: [к оглавлению](https://github.com/kontroler38/Project_3_Booking_review_AleksandF_v5/blob/main/README.md#Оглавление)

**Краткая информация о данных**
В датасете содержатся сведения о 515 000 отзывов на отели Европы. Модель, которую вы будете обучать, должна предсказывать рейтинг отеля по данным сайта Booking на основе имеющихся в датасете данных. Изученные навыки разведывательного анализа помогут улучшить модель.

Ссылка на страницу с данными в виде csv: (https://www.kaggle.com/competitions/sf-booking/data?select=hotels_test.csv)
- hotels_train.csv - набор данных для обучения (hotels_test.csv)
- hotels_test.csv - набор данных для оценки качества
- submission.csv - файл сабмишна в нужном формате

:arrow_up: [к оглавлению](https://github.com/kontroler38/Project_3_Booking_review_AleksandF_v5/blob/main/README.md#Оглавление)

### Этапы работы над проектом
- Подготовка датасета, а именно: очистка, анализ, проектирование признаков и их преобразование, 
- Обучение модели,
- Загрузить ноутбук со своим решением на Kaggle и GitHub, оформив его в соответствии с требованиями.
- Сдать проект на проверку и получить 21 балл.
- Получить обратную связь от команды курса.

:arrow_up: [к оглавлению](https://github.com/kontroler38/Project_3_Booking_review_AleksandF_v5/blob/main/README.md#Оглавление)

### Результат
Jupyter Notebook с выполненными заданиями и выводами: Kaggle(https://www.kaggle.com/code/kontroler38/project-3-booking-review-aleksandf-v5), GitHub(https://github.com/kontroler38/Project_3_Booking_review_AleksandF_v5/blob/main/Kaggle%20-%20v5.ipynb)

:arrow_up: [к оглавлению](https://github.com/kontroler38/Project_3_Booking_review_AleksandF_v5/blob/main/README.md#Оглавление)