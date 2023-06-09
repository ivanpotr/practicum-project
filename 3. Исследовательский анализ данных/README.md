# Продажа квартир в Санкт-Петербурге — анализ рынка недвижимости

### Цель исследования — факторы влияющие на стоимость квартиры. 

Для этого из изучим параметры:

Как быстро продавались квартиры
Факторы, больше всего влияющие на общую (полную) стоимость объекта
Подсчет средней цены одного квадратного метра в 10 населённых пунктах с наибольшим числом объявлений. Населённые пункты с самой высокой и низкой стоимостью квадратного метра.
Средняя цена каждого километра от центра в Санкт-Петербурге. Как стоимость объектов зависит от расстояния до центра города.

### Ход исследования:

Данные сервиса Яндекс.Недвижимость — архив объявлений о продаже квартир в Санкт-Петербурге и соседних населённых пунктов за несколько лет. По каждой квартире на продажу доступны два вида данных. Первые вписаны пользователем, вторые — получены автоматически на основе картографических данных. Например, расстояние до центра, аэропорта, ближайшего парка и водоёма.

Проверим данные на ошибки и оценим их влияние на исследование. Затем, на этапе предобработки вы поищем возможность исправить самые критичные ошибки данных.

Исследование пройдёт по следующим этапам:

Обзор данных. Предобработка данных. Добавление новых столбцов. Исследовательский анализ данных.

## Библиотеки и инструмены:

* `Python` 
* `Pandas`
* `Matplotlib`
* `Seaborn`
* `Преобработка данных`
* `Визуализация данных`
* `Исследовательский анализ данных`


## Общый вывод

Рассмотрел данные архива Яндекс.Недвижимость - объявления о продаже квартир в Санкт-Петербурге и соседних населённых пунктов за несколько лет.

Обработал полученный архив данных: обработал пропущенные значения там, где это необходимо, заменил типы данных на необходимые для удобной работы. Устранил редкие и выбивающиеся значения, поправил названия населённых пунктов.

Посчитал и добавил в таблицу цену квадратного метра жилья, вывел из даты дни недели, месяцы и года размещения объявлений, добавил категории по этажам квартир, перевел расстояние от центра города в километры.

Изучил факторы влияющие на стоимость квартиры: как быстро продавались квартиры, Факторы, больше всего влияющие на общую (полную) стоимость объекта, Подсчет средней цены одного квадратного метра в 10 населённых пунктах с наибольшим числом объявлений. Населённые пункты с самой высокой и низкой стоимостью квадратного метра, Средняя цена каждого километра от центра в Санкт-Петербурге. Как стоимость объектов зависит от расстояния до центра города.

Получаем следующие выводы:

Большинство квартир продается за первые 95 дней.
Главный критерий, влияющий на цену это размер квартиры, чем больше, тем дороже.
В Санкт - Петербурге самые дорогие квартиры.
Чем ближе квартиры к центру, тем дороже.
Важно учитывать, что, рассматривая среднюю стоимость квартир за определенные года, мы не рассматривали года по отдельности, а лишь смотрели средние показатели. Возможно, что цены на аналогичные квартиры в разных годах могли сильно отличаться.

Пропущено достаточно много значений, необходимо многие поля сделать обязательными для заполнения. Так же были аномальные значения, добавить проверку или ограничения на ввод данных, например для высоты потолка.