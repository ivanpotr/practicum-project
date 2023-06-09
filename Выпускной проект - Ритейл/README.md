# Ритейл — Анализ программы лояльности

Менеджер магазина строительных материалов "Строили, строили и наконец построили", отвечающий за программу лояльности клиентов, хочет оценить её эффективность.

### Цель исследования:

Необходимо проанализировать программу лояльности магазина.

### Задачи исследования:

Провести исследовательский анализ данных;
Провести анализ программы лояльности;
Сформулировать и проверить статистические гипотезы.

### Ход исследования:
Шаг 1. Загрузка данных и предобработка данных
Шаг 2. Анализ данных
Шаг 3. Анализ программы лояльности
Шаг 4. Проверка гипотез
Выводы и рекомендации

## Библиотеки и инструмены:

* `Python` 
* `Pandas`
* `Мatplotlib`
* `Seaborn`
* `Plotly`
* `Scipy`


## Общый вывод

Анализ программы лояльности:

Большинство покупателей предпочитают не участвовать в программе лояльности магазина.
Покупатели без карты лояльности чаще совершают покупки.
Среднее количество товаров на пользователя в месяц без карты лояльности выше, чем с ней.
Среднее количество товаров в одном чеке в месяц с картой лояльности выше, чем с без нее.
Программа лояльности стимулирует покупать больше товаров.
Средний чек без карты лояльности на графике по месяцам выше, чем с ней на протяжении всех месяцев наблюдений.
В рамках когортного анализа расчёта LTV выручка покупателей c картой лояльности меньше, чем у покупателей без карты лояльности.
В рамках когортного анализа расчёта LTV выручка покупателей c картой лояльности меньше, даже с учетом стоимости покупки карты.


Программа лояльности не работает, не повышает средний чек, но стимулирует брать большее количество товаров.

Проверка гипотиз:

По результатам статистического анализа установили, что в средних расходах и среднем количестве покупок у покупателей, участвующих в программе лояльности и нет, существуют статистически значимые различия, то есть клиенты не участвующие в программе лояльности тратят больше и покупают часто.

Программа лояльности не работает.

Рекомендации
Нужно поменять программу лояльности или совсем отказаться от нее.
Необходимо посмотреть данные за более продолжительный период, например за год, так как возможно покупатели с картой лояльности ждут начала сезона.
Стоит изучить большие или оптовые продажи.
В чеках содержится довольно много бесплатных товаров, если это всё подарки, то нужно выяснить насколько это окупается.