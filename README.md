# Проекты курса «Аналитик данных»
Этот репозиторий посвящен учебным проектам, которые я выполнила в рамках прохождения курса «Аналитик данных» в Яндекс.Практикум.

Программа курса помогла мне научиться исследовать, обрабатывать и систематизировать данные, выявлять закономерности, делать предположения и проверять гипотезы, создавать дашборды, прогнозировать и предсказывать события, а также четко формулировать основные выводы и давать рекомендации.

## Описание проектов
| Название проекта | Описание | Используемые библиотеки | 
| :---------------------- | :---------------------- | :---------------------- |
| [Исследование надёжности заёмщиков](https://github.com/alekseeva-julie/Yandex/tree/main/01.%20%D0%98%D1%81%D1%81%D0%BB%D0%B5%D0%B4%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5%20%D0%BD%D0%B0%D0%B4%D1%91%D0%B6%D0%BD%D0%BE%D1%81%D1%82%D0%B8%20%D0%B7%D0%B0%D1%91%D0%BC%D1%89%D0%B8%D0%BA%D0%BE%D0%B2) | Определила степень влияния семейного положения, количества детей, уровня дохода и цели кредита на факт его погашения в срок. Использовала лемматизацию, категоризацию и провела исследовательский анализ данных. | pandas, pymystem3, collections |
| [Исследование объявлений о продаже квартир](https://github.com/alekseeva-julie/Yandex/tree/main/02.%20%D0%98%D1%81%D1%81%D0%BB%D0%B5%D0%B4%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5%20%D0%BE%D0%B1%D1%8A%D1%8F%D0%B2%D0%BB%D0%B5%D0%BD%D0%B8%D0%B9%20%D0%BE%20%D0%BF%D1%80%D0%BE%D0%B4%D0%B0%D0%B6%D0%B5%20%D0%BA%D0%B2%D0%B0%D1%80%D1%82%D0%B8%D1%80) | Провела исследовательский анализ данных и определила параметры, влияющие на формирование рыночной стоимости объектов, для отслеживания аномалий и мошеннической деятельности на сайте сервиса. | pandas, numpy, seaborn, matplotlib |
| [Определение перспективного тарифа для телеком компании](https://github.com/alekseeva-julie/Yandex/tree/main/03.%20%D0%9E%D0%BF%D1%80%D0%B5%D0%B4%D0%B5%D0%BB%D0%B5%D0%BD%D0%B8%D0%B5%20%D0%BF%D0%B5%D1%80%D1%81%D0%BF%D0%B5%D0%BA%D1%82%D0%B8%D0%B2%D0%BD%D0%BE%D0%B3%D0%BE%20%D1%82%D0%B0%D1%80%D0%B8%D1%84%D0%B0%20%D0%B4%D0%BB%D1%8F%20%D1%82%D0%B5%D0%BB%D0%B5%D0%BA%D0%BE%D0%BC%20%D0%BA%D0%BE%D0%BC%D0%BF%D0%B0%D0%BD%D0%B8%D0%B8) | Проанализировала поведение пользователей разных тарифных планов по данным небольшой выборке (потраченные минуты, смс, интернет-трафик, выручка с каждого пользователя), визуализировала результаты, проверила несколько гипотез относительно различий в средней выручке пользователей. | pandas, numpy, seaborn, matplotlib, scipy |
| [Сборный Проект - 1](https://github.com/alekseeva-julie/Yandex/tree/main/04.%20%D0%A1%D0%B1%D0%BE%D1%80%D0%BD%D1%8B%D0%B9%20%D0%9F%D1%80%D0%BE%D0%B5%D0%BA%D1%82%20-%201) | Исследовала как менялись продажи по платформам и годам, определила актуальный "срок жизни" платформ, визуализировала данные, составила портрет пользователей для каждого региона, проверила гипотезы о разности пользовательских рейтингов разных платформ и наиболее популярных жанров. | pandas, numpy, seaborn, matplotlib, scipy |
| [Сбор и хранение данных](https://github.com/alekseeva-julie/Yandex/tree/main/05.%20%D0%A1%D0%B1%D0%BE%D1%80%20%D0%B8%20%D1%85%D1%80%D0%B0%D0%BD%D0%B5%D0%BD%D0%B8%D0%B5%20%D0%B4%D0%B0%D0%BD%D0%BD%D1%8B%D1%85) | Написала парсер для сбора данных с сайта, выгрузил данные из SQL, проанализировала спрос пассажиров на рейсы, определила популярные направления и модели самолетов, визуализировала результаты. | pandas, seaborn, matplotlib, requests, BeautifulSoup |
| [Анализ бизнес-показателей](https://github.com/alekseeva-julie/Yandex/tree/main/06.%20%D0%90%D0%BD%D0%B0%D0%BB%D0%B8%D0%B7%20%D0%B1%D0%B8%D0%B7%D0%BD%D0%B5%D1%81-%D0%BF%D0%BE%D0%BA%D0%B0%D0%B7%D0%B0%D1%82%D0%B5%D0%BB%D0%B5%D0%B9) | Применила когортный анализ, проанализировала основные бизнес-показатели и метрики продукта (MAU, WAU, DAU, Retention rate), продаж (средний чек, LTV) и маркетинга (CAC, ROMI), визуализировала изменения метрик во времени, дала рекомендации, как распределять бюджет.| pandas, numpy, seaborn, matplotlib |
| [Принятие решений в бизнесе на основе данных](E-https://github.com/alekseeva-julie/Yandex/tree/main/07.%20%D0%9F%D1%80%D0%B8%D0%BD%D1%8F%D1%82%D0%B8%D0%B5%20%D1%80%D0%B5%D1%88%D0%B5%D0%BD%D0%B8%D0%B9%20%D0%B2%20%D0%B1%D0%B8%D0%B7%D0%BD%D0%B5%D1%81%D0%B5%20%D0%BD%D0%B0%20%D0%BE%D1%81%D0%BD%D0%BE%D0%B2%D0%B5%20%D0%B4%D0%B0%D0%BD%D0%BD%D1%8B%D1%85) | Приоритизировала гипотезы с применением фреймворков ICE и RICE, запустила A/B-тесты по метрикам: выручке, среднему чеку, конверсии, посчитала статистическую значимость различий в метриках между группами по «сырым» и «очищенным» данным. | pandas, numpy, scipy.stats, datetime, matplotlib |
| [Рынок заведений общественного питания Москвы](https://github.com/alekseeva-julie/Yandex/tree/main/08.%20%D0%A0%D1%8B%D0%BD%D0%BE%D0%BA%20%D0%B7%D0%B0%D0%B2%D0%B5%D0%B4%D0%B5%D0%BD%D0%B8%D0%B9%20%D0%BE%D0%B1%D1%89%D0%B5%D1%81%D1%82%D0%B2%D0%B5%D0%BD%D0%BD%D0%BE%D0%B3%D0%BE%20%D0%BF%D0%B8%D1%82%D0%B0%D0%BD%D0%B8%D1%8F%20%D0%9C%D0%BE%D1%81%D0%BA%D0%B2%D1%8B) | Изучила распределение объектов общепита по типам заведений, принадлежности к сети, числу посадочных мест, местонахождению по улицам, использовала внешние источники данных, визуализировала полученные результаты, обрисовала перспективы открытия небольшого заведения и дала рекомендации. | pandas, numpy, re, BytesIO, requests, matplotlib, seaborn |
| [Сборный проект - 2](https://github.com/alekseeva-julie/Yandex/tree/main/09.%20%D0%A1%D0%B1%D0%BE%D1%80%D0%BD%D1%8B%D0%B9%20%D0%BF%D1%80%D0%BE%D0%B5%D0%BA%D1%82%20-%202) | Изучила поведение пользователей стартап-проекта, исследовала данные, проверила равномерность распределения пользователей по группам теста, изучила воронку продаж и определила последовательность событий, провела A/A/B-эксперимент, изучила его результаты и дала рекомендации. | pandas, numpy, math, scipy,matplotlib, seaborn, plotly |
| [Автоматизация](https://github.com/alekseeva-julie/Yandex/tree/main/10.%20%D0%90%D0%B2%D1%82%D0%BE%D0%BC%D0%B0%D1%82%D0%B8%D0%B7%D0%B0%D1%86%D0%B8%D1%8F) | Создала коннекцию к базе данных, написала SQL-запрос, выгрузила данные из базы в файл, сформировала дашборд в рамках автоматизации процесса еженедельной отчетности в соответствии с макетом и опубликовала на сайте Tableau Public. | pandas, psycopg2, sqlalchemy |
| [Прогнозы и предсказания](https://github.com/alekseeva-julie/Yandex/tree/main/11.%20%D0%9F%D1%80%D0%BE%D0%B3%D0%BD%D0%BE%D0%B7%D1%8B%20%D0%B8%20%D0%BF%D1%80%D0%B5%D0%B4%D1%81%D0%BA%D0%B0%D0%B7%D0%B0%D0%BD%D0%B8%D1%8F) | Провела исследовательский анализ данных и выявила признаки, влияющие на отток, построила модель бинарной классификации клиентов (Logistic Regression и Random Forest), оценила метрики accuracy, precision и recall и на основании алгоритма K-Means определила кластеры клиентов с характерными для них признаками, сформулировала базовые рекомендации по снижению оттока клиентов. | pandas, numpy, sklearn, scipy, matplotlib, seaborn |