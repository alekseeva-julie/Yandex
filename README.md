# Проекты курса «Аналитик данных»
Этот репозиторий посвящен учебным проектам, которые я выполнила в рамках прохождения курса «Аналитик данных» в Яндекс.Практикум.

Программа курса помогла мне научиться исследовать, обрабатывать и систематизировать данные, выявлять закономерности, делать предположения и проверять гипотезы, создавать дашборды, прогнозировать и предсказывать события, а также четко формулировать основные выводы и давать рекомендации.

## Описание проектов
| Название проекта | Описание | Используемые библиотеки | 
| :---------------------- | :---------------------- | :---------------------- |
| [Исследование надёжности заёмщиков](Credit_score) | Для определения степени влияния семейного положения, количества детей, уровня дохода и пр. на факт погашения кредита в срок, исходные данные были изучены и предобработаны, с помощью лемматизации определены цели получения кредита, определены возрастные группы клиентов и проведено исследование. Даны рекомендации для построения модели кредитного скоринга. | pandas, pymystem3, collections |
| [Исследование объявлений о продаже квартир](Real_estate) | Для определения параметров, влияющих на формирование рыночной стоимости объектов недвижимости, полученные данные были изучены и предобработаны, определено влияние площади, цены, числа комнат, высоты потолков и пр. на стоимость, обнаружены редкие и выбивающие значения, выявлен средний срок продажи объектов недвижимости, а также, установлены характеристики для очень быстрых и необычно долгих продаж, и выявлены населенные пункты с наибольшим числом объявлений. Сделан вывод о том, какие данные могут указывать на факт наличия мошеннической деятельности, связанной с продажей квартир.| pandas, numpy, seaborn, matplotlib |
| [Определение перспективного тарифа для телеком компании](Telecom) | Для ответа на вопрос "Какой тариф оператора сотовой связи лучше?", данные небольшой выборки были изучены и предобработаны, проанализировано поведение пользователей разных тарифных планов (потраченные минуты, смс, интернет-трафик, выручка с каждого пользователя), изучен объем услуг, требующийся пользователям каждого тарифа, и выявлено выходят ли они за рамки услуг, включенных в абонентскую плату. Проверено несколько гипотез относительно различий в средней выручке пользователей. | pandas, numpy, seaborn, matplotlib, scipy |
| [Сборный Проект - 1](Game_industry) | Проведен исследовательский анализ, который позволяет взглянуть на то, как менялись продажи по платформам и годам, за какой характерный срок появляются новые и исчезают старые платформы. Найден средний "срок жизни" платформ. Дан ответ на вопрос - "Влияют ли на продажи внутри одной популярной платформы отзывы пользователей и критиков?". Выявлены наиболее прибыльные жанры игр. Составлен портрет пользователя для каждого региона и проверено несколько гипотез, касающихся средних пользовательских рейтингов. | pandas, numpy, seaborn, matplotlib, scipy |
| [Сбор и хранение данных](Airline_analytics) | Написан парсер для сбора данных с сайта. Изучены полученные данные и на их основании проанализирован спрос пассажиров на рейсы в города России. Построены графики: модели самолетов и количество рейсов, города и количество рейсов, топ-10 городов и количество рейсов. Изучены предпочтения пользователей, покупающих билеты на те или иные направления. | pandas, seaborn, matplotlib, requests, BeautifulSoup |
| [Анализ бизнес-показателей](Afisha.yandex) | Для помощи коллегам снизить расходы — отказаться от невыгодных источников трафика и перераспределить бюджет были проанализированы основные бизнес-показатели и метрики продукта (MAU, WAU, DAU, Retention rate), продаж (средний чек, LTV) и маркетинга (CAC, ROMI). На графиках отражены изменения метрик во времени. На основе полученных результатов, даны рекомендации, куда и сколько им стоит вкладывать денег? | pandas, numpy, seaborn, matplotlib |
| [Принятие решений в бизнесе на основе данных](E-commerce) | В процессе работы с данными были приоритизированы гипотезы с применением фреймворков ICE и RICE. Запущены A/B-тесты по метрикам: выручке, среднему чеку, конверсии. Посчитана статистическая значимость различий в метриках между группами по «сырым» и «очищенным» данным. Проанализированы полученные результаты. | pandas, numpy, scipy.stats, datetime, matplotlib |
| [Рынок заведений общественного питания Москвы](Moscow_restaurants) | В рамках изучения текущего положение дел на рынке Москвы в сфере общественного питания были изучены характерные особенности объектов, пользующихся популярностью: распределение по типам заведений, принадлежность к сети, число посадочных мест, местонахождение по улицам. Использованы внешние данные с информацией по округам. Полученные результаты визуализированы. Обрисованы перспективы развития заведений и даны рекомендации. | pandas, numpy, re, BytesIO, requests, matplotlib, seaborn |
| [Сборный проект - 2](Online_store) | В рамках изучения поведения пользователей стартап-проекта, который продаёт продукты питания, был проведен исследовательский анализ данных, проверено распределение пользователей по всем группам теста, изучена воронку продаж и определена последовательность событий, проведен A/A/B-эксперимент, изучена его результаты и даны рекомендации. | pandas, numpy, math, scipy,matplotlib, seaborn, plotly |
| [Автоматизация](Zen.yandex_project) | Для автоматизации процесса еженедельной отчетности была создана коннекция к базе данных, выполнен SQL-запрос, выгружены данные из базы в файл, сформирован дашборд в соответствии с макетом и опубликован на сайте Tableau Public. | pandas, psycopg2, sqlalchemy |
| [Прогнозы и предсказания](Fitness_сlubs_project) | В рамках изучения оттока клиентов был проведен исследовательский анализ данных, построена модель прогнозирования оттока и сформированы типичные портреты клиентов: выделено несколько наиболее ярких групп и охарактеризованы их основные свойства. Сформулированы основные выводы и даны базовые рекомендации по повышению качества работы с клиентами: предложены меры по снижению оттока и определены особенности взаимодействия с клиентами. | pandas, numpy, sklearn, scipy, matplotlib, seaborn |
