###  Даны данные о взаимодействий с рекламными объявлениями на некоторой площадке за 6 дней. И таблица с характеристиками рекламных клиентов (тех, кто разместил эти объявления).

### Были получены ответы на следующие вопросы:
1. Какое среднее количество показов и среднее количество кликов на объявления за весь период?
2. Какое значение скользящего среднего получим за 6 апреля 2019 года? 
3. Есть ли аномалии в данных?
4. Какое среднее количество дней от даты создания рекламного клиента и первым запуском рекламного объявления этим клиентом?
5. Чему равна конверсия от создания рекламного клиента в запуск первой рекламы в течение не более 365 дней?
6. Cколько уникальных клиентов запустили свое первое объявление в первый месяц своего существования?

### Используемые инструменты

pandas, numpy, seaborn, matplotlib

### Выводы

- В среднем только на 9 показ рекламного объявления совершается клик
- Наибольшее количество средних показов совершилось 5 апреля
- Была надена аномалия в данных. Данные рекламной кампании 112583 сильно отличаются и по показам, и по кликам, и по аудитории. Требуется дополнительная проверка этих данных.
- Среднее количество дней от даты создания рекламного клиента и первым запуском рекламного объявления равно 124 дням
- В течение первого года рекламу запускают менее одного процента от всех созданных рекламных кабинетов
- Из них в первый месяц запускают рекламу 1,3%, а основная масса рекламных объявлений запускается в промежутке от 90 до 180 дней - 47 %.