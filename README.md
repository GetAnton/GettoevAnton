# Praktikum
## Избранные проекты из курса Яндекс.Практикум по специализации Аналитик Данных

Проект | Задачи проекта | Описание проекта | Что было использовано
--- | --- | --- | ---
[ Продажа квартир в Санкт-Петербурге — анализ рынка недвижимости](https://github.com/GetAnton/GettoevAnton/tree/practicum/Apartments%20sales%20analysis)| Используя данные сервиса Яндекс.Недвижимость, необходимо выделить те параметры квартир, которые помогут автоматизированной системе определить мошенников. | В проекте была проведена предобработка данных, добавлены новые параметры оценки объявлений, на основе которых была проанализирована база данных по квартирам. Построены гистограммы, боксплоты, диаграммы рассеивания, с помощью которых были выделены критерии для поддержки автоматической системы. | Pandas, Matplotlib, Numpy
[ Анализ пользовательского поведения в мобильном приложении стартапа](https://github.com/GetAnton/GettoevAnton/tree/practicum/AB%20test%20project) | На основе данных использования мобильного приложения для продажи продуктов питания необходимо проанализировать воронку продаж, а также оценить результаты A/A/B-тестирования | В данном проекте были изучены принципы событийной аналитики. Была построена воронка продаж, исследован путь пользователей от первого "захода" на страницу до покупки товара. После результатов анализа А/В-теста был сделан вывод, что внедрение новых шрифтов не влияет на поведение пользователей.|  Pandas, Matplotlib, Numpy, Seaborn, Plotly, A/B-тест
[ Анализ убытков от рекламной компании приложения](https://github.com/GetAnton/GettoevAnton/tree/practicum/Mobile%20app%20analysis) | Задача для маркетингового аналитика развлекательного приложения Procrastinate Pro+. Несмотря на огромные вложения в рекламу, последние несколько месяцев компания терпит убытки. Необходимо разобраться в причинах убытков и помочь компании выйти в плюс | Проведен анализ данных, на основе которого рассчитаны различные метрики; использован когортный анализ: LTV, CAC, Retention rate, DAU, WAU, MAU и т.д. Использованы готовые функции расчёта метрик, на основе которых сделаны выводы о дальнейшей стратегии компании |  Pandas, Matplotlib, Numpy, Статистический тест, Когортный Анализ
[Изучение закономерностей, определяющих успешность игр ](https://github.com/GetAnton/GettoevAnton/tree/practicum/Games%20sales%20analysis) | Используя исторические данные о продажах компьютерных игр, оценки пользователей и экспертов,а также жанры и платформы, необходимо выявить закономерности, определяющие успешность игры в объемах продаж  | Выявлены параметры, определяющие успешность игры в разных регионах мира. На основании этого подготовлен отчет для магазина компьютерных игр для планирования рекламных кампаний. Проведена предобработка данных, выбран актуальный период для анализа, составлены портреты пользователей каждого региона. Проверены гипотезы: средние пользовательские рейтинги платформ Xbox One и PC одинаковые; средние пользовательские рейтинги жанров Action и Sports разные. При анализе был использован критерий Стьюдента для независимых выборок|  Pandas, Matplotlib, Numpy
[Исследование надёжности заёмщиков банка](https://github.com/GetAnton/GettoevAnton/tree/practicum/Credit%20reliablity%20analysis) | Используя статистику банка о платежеспособности клиентов, необходимо разобраться, влияет ли семейное положение и количество детей клиента на факт погашения кредита в срок.  | Выполнена предобработка данных, проведена лемматизация ключевых слов, проведена категоризация данных, построены графики на основе обработанных данных. Сделаны выводы, где указаны категории клиентов, наиболее склонных к нарушению условий кредитования, а также категории, в надежности которых можно не сомневаться. |  Pandas, Matplotlib, Numpy
[Определение перспективного тарифа для телеком-компании ](https://github.com/GetAnton/GettoevAnton/tree/practicum/Perspective%20tariff%20analysis) | На основе данных о клиентах телеком-компании, нужно проанализировать использование текущих тарифов и сделать вывод - какой тариф выгоден компании.  | В проекте выполнена предобработка данных; используя функции, посчитано потребление клиентами пакетов услуг; по каждому типу трафика проведен анализ данных, на основе которого произведен расчёт того, какой тариф приносит больше всего прибыли для компании, а какой наименее выгоден. |  Pandas, Matplotlib, Numpy,  Scipy
