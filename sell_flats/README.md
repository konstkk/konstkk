## Исследование объявлений о продаже квартир 

Идея проекта:
На основе архива объявлений о продаже квартир в Санкт-Петербурге и соседних населённых пунктов за несколько лет необходимо построить автоматизированную систему определения стоимости объектов недвижимости. 

Цель исследования:
Определение рыночной стоимости объектов недвижимости

Задачи исследования:
1.Выявление зависимости между стоимостью объектов недвижимости и различными факторами (характеристиками объектов недвижимости). 


### План проекта

1.	Исследование данных 
2.	Предобработка данных 
3.	Расчет новых показателей
4.	Исследовательский анализ 
5.	Вывод



### Использованные библиотеки

pandas


### Состав датасета

RangeIndex: 23699 entries, 0 to 23698
- total_images            23699 non-null int64
- last_price              23699 non-null float64
- total_area              23699 non-null float64
- first_day_exposition    23699 non-null object
- rooms                   23699 non-null int64
- ceiling_height          14504 non-null float64
- floors_total            23613 non-null float64
- living_area             21796 non-null float64
- floor                   23699 non-null int64
- is_apartment            2775 non-null object
- studio                  23699 non-null bool
- open_plan               23699 non-null bool
- kitchen_area            21421 non-null float64
- balcony                 12180 non-null float64
- locality_name           23650 non-null object
- airports_nearest        18157 non-null float64
- cityCenters_nearest     18180 non-null float64
- parks_around3000        18181 non-null float64
- parks_nearest           8079 non-null float64
- ponds_around3000        18181 non-null float64
- ponds_nearest           9110 non-null float64
- days_exposition         20518 non-null float64