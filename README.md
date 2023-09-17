# Портфолио: аналитик данных

# Обо мне
Привет! Меня зовут Дмитрий, я начинающий аналитик данных. В этом репозитории вы можете найти некоторые из моих проектов, выполненных во время обучения и практики.


## Навыки и технологии
* Инструменты анализа данных: SQL, Excel:
* Языки программирования и библиотеки: Python, Pandas, Numpy, math и др.
* Системы управления базами данных: MySQL, PostgreSQL
* Средства визуализации данных: PowerBi, Matplotlib, seaborn
* Инструменты для машинного обучения: scikit-learn, TensorFlow


# Боевые pet-проекты
## Проект 1: Социологическое исследование условий труда (Python, SQL)
Исследование проводилось среди сотрудников одного департамента в 1200 человек.

#### Файл с кодом: https://github.com/azarovdimka/python/blob/master/Аналитика%20данных/teleopros/opros_bot.py

#### Отчеты и выводы исследования: https://drive.google.com/drive/folders/1EvkoBguP5YL7BRKlerruqf4Y1ccipLw6?usp=sharing



## Проект 2: Информационно-справочный Telegram-бот (Python, SQL, REST API)
Этот бот был разработан для бортпроводников Авиакомпании "Россия", присылал уведомления, содержал десятки функций, команд, меню, парсил удаленный корпоративный сайт, содержал ответы более чем на 1000 вопросов. Имел многоступенчатую систему обработки запроса и поиска информации. 

#### Основной исполняемый скрипт с кодом: https://github.com/azarovdimka/python/blob/master/telebot/flight_bot.py

#### Репозиторий со всеми файлами: https://github.com/azarovdimka/python/tree/master/telebot

#### Презентация бота: https://docs.google.com/presentation/d/1qUIiPn30K5sND8BxLDoCqi-ieNaTlZHk/edit?usp=sharing&ouid=109121693020713627795&rtpof=true&sd=true


# Учебные проекты 
## Проект 1: Калькулятор юнит-экономики онлайн-школы (Excel)

#### Что нужно было сделать:
1) Добавить в калькулятор в список параметров показатель "Поправочный коэф-т на привлечение"
2) Настроить динамический расчёт количества новых студентов
3) Просчитать сценарий, при котором планы маркетинга будут увеличены на 12% (настройки остальных показателей не меняются)
4) Добавить в калькулятор Найма и пропускной способности возможность изменять параметры
5) Обновитб прогнозное количество уроков, добавив новые значения
6) Просчитайте сценарий, при котором Пропускная способность П увеличится на 15 процентов, а Retention П упадёт на 2 процента
7) С помощью Поиска решений составить новый план найма с ограничением: за месяц нельзя нанять более 70 преподавателей

#### Как решал: применял сводные таблицы, надстройку "поиск решений", различные встроенные формулы, визуализацию. 

#### Ссылка на проект https://github.com/azarovdimka/dataanalysis/blob/main/Калькулятор%20юнит-экономика%20онлайн-школы.xlsx

#### Итоги: Расчитана рентабельность и иные показатели. Получены прогнозные результаты. Скоректирвоаны показатели работы.



## Проект 2: Калькулятор юнит-экономики онлайн-кинотеатра (Excel)

#### Задача:
1) Просчитать юнит-экономику продукта;
2) Предложить сценарий по настройке параметров для выхода на 25-ти процентную маржинальность; 
3) Визуализировать какие пользователи, где и в каком объеме смотрят фильмы на платформе.
   
#### Как решал: применял сводные таблицы, различные встроенные формулы, визуализацию. 

#### Ссылка на проект: https://github.com/azarovdimka/dataanalysis/blob/main/Юнит-экономика%20онлайн-кинотеатра.xlsx

#### Итоги: Расчитана рентабельность и иные показатели. Получены прогнозные результаты. Скоректирвоаны показатели работы.



## Проект 3: Когортный анализ онлайн-кинотеатра с помощью SQL

Задача: 
Выявить количество транзакций от партнеров по когортам: от какого банка и пробный период или нет.

Как решал: 
1) Ознакомился с БД;
1) Сгруппировал по когортам;
2) Расставил ранги по двум шкалам при помощи оконных (аналитических) функций;
3) Произвел соответсвующие расчеты;
4) Построил распределение.

#### Ссылка на проект: https://github.com/azarovdimka/dataanalysis/blob/main/SQL%20Когортный%20анализ.txt



## Проект 4: Построение витрины для модели машинного обучения в банке с помощью SQL

#### Как решал:
1) Построил распределение выплаченных денег клиентами по месяцам;
2) Рассчитал три скользящих средних на основе прошлых и будущих плтежей;
3) Выбрал поля, раздал идентификаторы;
4) Использовал агрегирующие и оконные (аналитические) функции, кейс вены, джоины

#### Ссылка на проект: https://github.com/azarovdimka/dataanalysis/blob/main/SQL%20Построение%20витрины%20для%20модели%20машинного%20обучения%20в%20банке.txt



## Проект 5: Моделирование изменения балансов студентов в SQL

#### Задача:
Смоделировать изменение баланса уроков каждого студента: cколько всего за каждый день;
как менялось при транзакциях и по мере прохождения уроков.
В результате запрос собирает данные о балансах студентов за каждый "прожитый" ими день.

#### Как решал: 
1) Составил список вопросов и гипотез;
2) Применял джоины, оконные (аналитические) функции, группировки, визуализацию, когортный анализ

#### Ссылка на проект и выводы: https://github.com/azarovdimka/dataanalysis/blob/main/SQL%20Моделирование%20балансов%20в%20онлайн-школе%20Выводы%20Курсовая.xlsx



## Проект 6: Исследование надёжности заёмщиков в Python

#### Задача: 
Кредитный отдел банка хочет разобраться, влияет ли семейное положение и количество детей клиента на факт погашения кредита в срок. Входные данные от банка — статистика о платёжеспособности клиентов. Результаты исследования будут учтены при построении модели кредитного скоринга — специальной системы, которая оценивает способность потенциального заёмщика вернуть кредит банку.

#### Как решал:
1) Открыл датасет, изучил общую информацию;
2) Предобработка данных (пропуски, замена типов, дубликаты, лемматизация, категоризация);
3) Поиск взаимосвязей и ответов на поставленные вопросы (перегруппировка данных, сводные таблицы по условию);
4) Написание промежуточных и общих выводов по ходу исследования.

#### Ссылка на исследование:
https://github.com/azarovdimka/dataanalysis/blob/main/Проект%20Должники.ipynb


## Проект 7: Определение перспективного тарифа в телеком-компаии в Python

#### Задача: 
Определить перспективный тариф для оператора сотовой связи, какой тариф приносит больше прибыли?

#### Как решал:
1) Анализ и предобработка данных из различных датасетов (пропуски, замена типов, дубликаты, пердварительные расчеты, describe, категоризация);
2) Поиск ответов на поставленные вопросы (поиск взаимосвязей при помощи перегруппировки данных, сводных таблиц по условию);
3) Оперировал данными из нескольких датасетов;
4) Использовал визуализацию: гистограммы, боксплоты;
5) Применил t-критерий Стьюдента в сравнительном анализе;
6) Рассмотрел различные гипотезы;
7) Написание промежуточных и общих выводов по ходу исследования.

Ссылка на исследование:
https://github.com/azarovdimka/dataanalysis/blob/main/Абоненты%20сотовой%20связи.ipynb



## Проект 8: Определение перспективных направлений в играх в Python

#### Задача: 
На основании данных из открытых источников за 2016 год (о продажах игр, оценки пользователей и экспертов, жанры и платформы, например, Xbox или PlayStation), выявить закономерности, определяющие успешность игры. Это позволит сделать ставку на потенциально популярный продукт и спланировать рекламные кампании.


#### Как решал:
1) Извлечение и обзор данных;
2) Предобработка данных (пропуски, замена типов, дубликаты, пердварительные расчеты, describe, категоризация);
3) Исследовательский анализ данных;
4) Поиск корреляции и взаимосвязи, ответов на поставленные вопросы (группировки, графики, сводные таблицы);
5) Применил t-критерий Стьюдента в сравнительном анализе и гипотезы;
6) Использовал визуализацию (графики): plot, боксплоты, seaborn, scatter, pie;
7) Формировал типичные портреты игроков по регионам;
7) Написание промежуточных и общих выводов по ходу исследования.

#### Ссылка на исследование:
https://github.com/azarovdimka/dataanalysis/blob/main/Перспективные%20направления%20в%20играх.ipynb



### Вывод:
Обладаю необходимыми навыками и компетенциями. Готов анализировать большие объемы информации и искать ответы на вопросы, исследовать различные темы.


### Контактная информация
Email: dmi-azarov@ya.ru
Telegram: https://t.me/analystazarov
