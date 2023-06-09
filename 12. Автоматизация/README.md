# Дашборд для Яндекс.Дзен

Необходимо помочь менеджерам Яндекс.Дзен ответить на следующие вопросы:

- Сколько взаимодействий пользователей с карточками происходит в системе с разбивкой по темам карточек?
- Как много карточек генерируют источники с разными темами?
- Как соотносятся темы карточек и темы источников?

Указанные выше вопросы возникают с постоянной переодичностью, в следствие чего, было принято решение создать дашборд в соответсвии с ТЗ:

- Бизнес-задача: анализ взаимодействия пользователей с карточками Яндекс.Дзен;
- Насколько часто предполагается пользоваться дашбордом: не реже, чем раз в неделю;
- Кто будет основным пользователем дашборда: менеджеры по анализу контента;
- Состав данных для дашборда:
  - История событий по темам карточек (два графика - абсолютные числа и процентное соотношение);
  - Разбивка событий по темам источников;
  - Таблица соответствия тем источников темам карточек;
- По каким параметрам данные должны группироваться:
  - Дата и время;
  - Тема карточки;
  - Тема источника;
  - Возрастная группа;
- Характер данных:
  - История событий по темам карточек — абсолютные величины с разбивкой по минутам;
  - Разбивка событий по темам источников — относительные величины (% событий);
  - Соответствия тем источников темам карточек - абсолютные величины;
- Важность: все графики имеют равную важность;
- Источники данных для дашборда: cырые данные о событиях взаимодействия пользователей с карточками (таблица log_raw);
- База данных, в которой будут храниться агрегированные данные: дополнительные агрегированные таблицы в БД zen;
- Частота обновления данных: один раз в сутки, в полночь по UTC;
- Какие графики должны отображаться и в каком порядке, какие элементы управления должны быть на дашборде (макет дашборда)

## [Дашборд](https://public.tableau.com/app/profile/vanya.potorochin/viz/dash_visits_16758906666140/Dashvisits?publish=yes])

## Инструменты для исследования:

 * `Pandas`
 * `Sqlalchemy`
 * `SQL`
 * `Tableau` 