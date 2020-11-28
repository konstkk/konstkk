## Определение перспективного тарифа для телеком компании 

Заказчик — федеральный оператор сотовой связи. Клиентам предлагают два тарифных плана: «Смарт» и «Ультра». 
Чтобы скорректировать рекламный бюджет, коммерческий департамент хочет понять, какой тариф приносит больше денег.

Цель исследования:
Определить, какой тариф приносит больше денег.

Задачи исследования:
1.Проведение предварительного анализа тарифов на небольшой выборке клиентов 
2.Проверка гипотезы о равенстве среднего тарифа по Москве и среднего тарифа по России.


### План проекта

1.	Изучение данных
2.	Предобработка данных
3.	Расчет новых показателей
4.	Формирование рабочей таблицы
5.	Анализ данных
6.	Проверка гипотез
7.	Выводы


### Использованные библиотеки

pandas

### Состав датасета

RangeIndex: 500 entries, 0 to 499
- user_id       500 non-null int64
- age           500 non-null int64
- churn_date    38 non-null object
- city          500 non-null object
- first_name    500 non-null object
- last_name     500 non-null object
- reg_date      500 non-null object
- tariff        500 non-null object

RangeIndex: 202607 entries, 0 to 202606
- id           202607 non-null object
- call_date    202607 non-null object
- duration     202607 non-null float64
- user_id      202607 non-null int64

RangeIndex: 123036 entries, 0 to 123035
- id              123036 non-null object
- message_date    123036 non-null object
- user_id         123036 non-null int64

RangeIndex: 149396 entries, 0 to 149395
- Unnamed: 0      149396 non-null int64
- id              149396 non-null object
- mb_used         149396 non-null float64
- session_date    149396 non-null object
- user_id         149396 non-null int64

RangeIndex: 2 entries, 0 to 1
- messages_included        2 non-null int64
- mb_per_month_included    2 non-null int64
- minutes_included         2 non-null int64
- rub_monthly_fee          2 non-null int64
- rub_per_gb               2 non-null int64
- rub_per_message          2 non-null int64
- rub_per_minute           2 non-null int64
- tariff_name              2 non-null object