# Никита Самыловский

**Аналитика данных · SQL · Python**

Сейчас работаю стажёром-аналитиком в Яндексе и учусь на втором курсе ПМИ ФКН ВШЭ.
До этого три месяца работал Junior ML Engineer: готовил данные, проверял результаты обработки и разбирал расхождения с помощью SQL и pandas.

Интересны продуктовые эксперименты, поведение пользователей и качество поиска. В проектах ниже можно посмотреть мои запросы, расчёты и выводы.

[![Telegram](https://img.shields.io/badge/Telegram-neo__ybt-26A5E4?style=flat-square&logo=telegram&logoColor=white)](https://t.me/neo_ybt)
[![Email](https://img.shields.io/badge/Email-написать-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:nikitasamilovsky@gmail.com)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Nikita_Samylovsky-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/nikita-samylovsky/)

## Инструменты

**Данные и расчёты**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=for-the-badge&logo=scipy&logoColor=white)

**Среда и визуализация**

![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![DuckDB](https://img.shields.io/badge/DuckDB-FFF000?style=for-the-badge&logo=duckdb&logoColor=black)
![Matplotlib](https://img.shields.io/badge/Matplotlib-365C88?style=for-the-badge)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

SQL: CTE, оконные функции, объединения таблиц, подготовка витрин. Аналитика: A/B-тесты, доверительные интервалы, конверсия, когорты, retention, NDCG и MRR.

## Проекты

| Проект | Что разбирал | Результаты |
| :--- | :--- | :--- |
| [A/B-тест бронирования](https://github.com/Winlak/carsharing-ab-test-analysis) | Как оценить влияние подсказки на конверсию и проверить отмены и время бронирования | [Отчёт](https://github.com/Winlak/carsharing-ab-test-analysis/blob/main/reports/analysis_report.md) |
| [Качество поиска](https://github.com/Winlak/search-ranking-quality-analysis) | Как сравнить выдачу и найти запросы, на которых результат ухудшился при росте общей метрики | [Отчёт](https://github.com/Winlak/search-ranking-quality-analysis/blob/main/reports/analysis_report.md) |
| [Воронка первой поездки](https://github.com/Winlak/carsharing-activation-funnel-analysis) | На каких шагах теряются пользователи и чем отличаются платформы и города | [Отчёт](https://github.com/Winlak/carsharing-activation-funnel-analysis/blob/main/reports/analysis_report.md) |
| [Пустая выдача](https://github.com/Winlak/search-zero-results-investigation) | Как отделить изменение состава трафика от изменений показателя внутри сегментов | [Отчёт](https://github.com/Winlak/search-zero-results-investigation/blob/main/reports/analysis_report.md) |
| [Удержание пользователей](https://github.com/Winlak/carsharing-retention-cohort-analysis) | Как считать D1/D7/D30 и сравнивать когорты с разным временем наблюдения | [Отчёт](https://github.com/Winlak/carsharing-retention-cohort-analysis/blob/main/reports/analytical_report.md) |
| [Загрузка автопарка](https://github.com/Winlak/carsharing-fleet-utilization-analysis) | Где спрос на поездки расходится с доступностью машин по районам и времени суток | [Репозиторий](https://github.com/Winlak/carsharing-fleet-utilization-analysis) |

Это учебные проекты на сгенерированных данных. В репозиториях есть генераторы, тесты и инструкции запуска.

## Пример анализа

Воронка из проекта про первую поездку. На графике — доля зарегистрировавшихся пользователей, дошедших до каждого шага. Итоговая конверсия — 25,6%.

[![Воронка первой поездки: от регистрации до завершённой поездки](https://raw.githubusercontent.com/Winlak/carsharing-activation-funnel-analysis/main/reports/figures/funnel_overall.png)](https://github.com/Winlak/carsharing-activation-funnel-analysis/blob/main/reports/analysis_report.md)

В [отчёте](https://github.com/Winlak/carsharing-activation-funnel-analysis/blob/main/reports/analysis_report.md) отдельно разобрал абсолютные потери, конверсию между шагами и различия по сегментам.
