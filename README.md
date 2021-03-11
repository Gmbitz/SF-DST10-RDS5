# Проект 5. Выбираем авто выгодно

## Описание проекта:
Представьте, что вы работаете в компании, которая занимается продажей автомобилей с пробегом. Основная задача компании и ее менеджеров - максимально быстро находить выгодные предложения (проще говоря, купить ниже рынка, а продать дороже рынка).

Вам поставлена задача создать модель, которая будет предсказывать стоимость автомобиля по его характеристикам.
Если наша модель работает хорошо, то мы сможем быстро выявлять выгодные предложения (когда желаемая цена продавца ниже предсказанной рыночной цены). Это значительно ускорит работу менеджеров и повысит прибыль компании.

А где данные для обучения модели?
Так исторически сложилось, что компания изначально не собирала данные. Есть только небольшой датасет с историей продаж, которого для обучения модели будет явно мало. Его мы будем использовать для теста (В ЛидерБорде), остальное придется собрать самим… Вспоминаем модуль по парсингу сайтов или ищем готовые датасеты.

Условия соревнования:
- Данное соревнование является бессрочным и доступно для всех потоков.
- Срок выполнения соревнования устанавливаеться индивидуально в каждом потоке.
- Тестовая выборка представлена в ЛидерБорде целиком.
- По этому лучшие и победные решения буду проверяться на их "адекватность" (чтоб не было подгонки под тестовую выборку).
- Разрешено использовать внешние данные. (но их источник должен быть публичным и доступен всем участникам соревнования)
- Разрешено использовать любые ML алгоритмы и библиотеки. (кроме DL)
- Даже если удасться найти исходные объявления из теста - нельзя просто указать их цену. Делаем реальный ML продукт, который потом сможет нормально работать на новых данных.

Дополнительно:
Обратите внимание, что к данному соревнованию прилагается Baseline, который может помочь сформировать вам собственное победное решение

Метрика:
MAPE - Расшифровывается выражение как средний абсолютный процент ошибки или средняя относительная ошибка прогноза (Mean Absolute Percentage Error, MAPE)

![image](https://user-images.githubusercontent.com/69968225/110718495-236d6880-821c-11eb-969c-0b71c4874af2.png)

Где:
- Y_t – фактический значение за анализируемый период;
- Ŷ_t — значение прогнозной модели за анализируемый период;
- n — количество периодов.

[Ссылка](https://www.kaggle.com/c/sf-dst-car-price-prediction) на соревнование с тестовым датасетом

[Ссылка](https://www.kaggle.com/gmbitz/all-auto-ru-09-09-2020) на тренировочный датасет
