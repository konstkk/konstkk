## Оптимизация маркетинговых затрат Яндекс.Афиши

Заказчик — Яндекс.Афиша. 

Цель исследования:
Разработка рекомендаций по совершенствованию маркетинговой стратегии Яндекс.Афиши

Задачи исследования:
1.Изучение поведения пользователей. 
2.Определение прибыльности рекламных источников.

### План проекта

1.	Загрузка и анализ данных
2.	Предобработка данных
3.	Расчет метрик 
3.1. 	Продукт 
3.2. 	Продажи 
3.3. 	Маркетинг
4.	Выводы

### Использованные библиотеки

pandas, numpy, matplotlib, seaborn

### Состав датасета

RangeIndex: 359400 entries, 0 to 359399
- Device       359400 non-null object
- End Ts       359400 non-null object
- Source Id    359400 non-null int64
- Start Ts     359400 non-null object
- Uid          359400 non-null uint64

RangeIndex: 50415 entries, 0 to 50414
- Buy Ts     50415 non-null object
- Revenue    50415 non-null float64
- Uid        50415 non-null uint64

RangeIndex: 2542 entries, 0 to 2541
- source_id    2542 non-null int64
- dt           2542 non-null object
- costs        2542 non-null float64