# Портфолио: аналитик данных

## Обо мне 

Привет! Меня зовут Аделия, я начинающий аналитик данных. 

В этом репозитории вы можете найти некоторые из моих проектов, выполненных во время обучения и практики.
<br>

## Навыки и технологии
- Инструменты анализа данных: ``SQL``, ``Excel``: 
- Системы управления базами данных: ``MySQL``, ``PostgreSQL``
- Средства визуализации данных: ``PowerBi``



## Проекты
<p> Проект 1: Калькулятор юнит-экономики онлайн-кинотеатра</p>
<p>Что нужно было сделать: Просчитать юнит-экономику продукта и предложить сценарий по настройке параметров для выхода на 25-ти процентную маржинальность. 
Также важно визуализировать какие пользователи, где и в каком объеме смотрят фильмы на платформе. <p>
<ol>
  <li>Задача №1.Определить, что является юнитом в нашей экономике.
  <li>Задача №2.Посчитать юнит-экономику продукта и предложить сценарий по настройке параметров для выхода на 25%-ную маржинальность.
  <li>Задача №3.Выбрать оптимальный вариант расчета Retention. 
  <li>Задача №4.Собрать визуализации основных бизнес-показателей.
  <li>Задача №5.Исследовать данные о пользователях и их поведении.
</ol>

<p>Как решала: Решила задачи, связанные с исследованием аудитории и расчетов метрик, которые помогут нам оценить динамику изменения просмотров на нашей платформе.
Просчитала определенные метрики (количество повторных оплат в каждом месяце, Retention для каждого месяца, среднее геометрическое Retention, Лайфтайм, LTR, CAC, маржинальность)для создания калькулятора юнит-экономики.
Подогнала параметры таким образом, чтобы маржинальность была +25%. Построила графики и оформила презентацию для визуализации результатов.<p>

Ссылка на проект:
> https://github.com/Badretdinova/Analyst/blob/main/Бизнес%20модель%20работы%20кинотеатра.pptx

<p>Выводы (итоги):<p>
<ol>Рассчитав юнит-экономику, мы увидели, что маржинальность данного онлайн-кинотеатра составила -94%.
Для того, чтобы выйти на +25% маржинальность нужно повысить Retention на 13%, стоимость подписки повысить на 25%, а также уменьшить САС на 10%.
</ol>  
<br> 
</p> 

<p>Проект 2: Калькулятор юнит-экономики онлайн-школы</p>
<p>Что нужно было сделать:  собрать калькулятор юнит-экономики. 
                            выйти на 4000 активных студентов,
                            удержать маржинальность на уровне выше 15%,
                            выйти на выручку выше 35 000 000 руб. в месяц,
                            увеличить зарплату преподавателей.
<ol>
  <li> Задача №1. Собрать все данные для составления калькулятора (средний CPA, конверсия в покупку, средний CAC, Retention, LT, интенсивность, LT(уроки), стандартная цена 1 урока,доля скидок, фактическая цена за 1 урок, плата учителю за 1 урок, LTR, CAC%, ЗП Учителей%, ФОТ%, Маржа%).
 <li> Задача №2. Сделать систему, где параметры взаимосвязаны и изменение одного сразу влечет за собой изменение другого. 
 <li> Задача №3. Составить прогноз на следующий год с помощью данных, которые мы получили ранее.
</ol>

<p>Как решала: <ol> <li>Подготовила базу для решения.
<li>Проанализировала исторические данные и собрала с помощью сводных таблиц: количество уроков, количество студентов, количество новых студентов, среднюю цену одного урока.
<li>Провела расчет сложных композитных показателей: LT, LTR, CAC.
<li>Свела воедино полученную информацию по юнит-экономике и рассчитала доли статей.
<li> Чтобы рассчитать прогноз на год вперед для калькулятора, подготовила пространство для расчета (протянула столбец Месяцы на год (расчетный период) вперед).
<li>Вывела показатели: средний CPA, конверсия в покупку, средний CAC, Retention, LT, интенсивность, LT(уроки), стандартная цена 1 урока, доля скидок, фактическая цена за 1 урок, плата учителю за 1 урок, LTR, CAC%, ЗП Учителей%, ФОТ%. Из трех последних показателей мы получаем маржинальность.
<li>На основании нашего периода рассчитывается «Факт», то есть фактические значения всех показателей. Считаем все показатели «как есть».
<li>Оформила эти результаты (при необходимости) и настроила для них форматирование.
<li>Создаем колонку, где параметры взаимосвязаны и изменение одного сразу влечет за собой изменение другого (изменение в процентах).
<li>Строим прогноз: Заполнила таблицу данными о Retention и интенсивности на прогнозный период. Применила условное форматирование для результатов и изменяемых коэффициентов,связала показатели с данными.
<li>С помощью показателей LTR, CAC%, ЗП Учителей%, ФОТ%, Маржа% визуализируем юнит-экономику.
 </ol> 
  <p> 
  
Ссылка на проект:
> https://github.com/Badretdinova/Analyst/blob/main/Сборка%20калькулятора%20юнит-экономики-2.xlsx
 
<p>Выводы (итоги):<p>
<ol>
  Применять все полученные знания и навыки для формирования универсального аналитического инструмента — калькулятора юнит-экономики.
  Готовить полезные отчеты для бизнеса.
</ol>
<br> 
</p> 

<p>Проект 3: Моделирование изменения балансов студентов с помощью SQL</p> 
<p>Что нужно было сделать: смоделировать изменение балансов студентов.
Чтобы проверить, всё ли в порядке с данными, составить список гипотез и вопросов, важно понимать: 
- сколько всего уроков было на балансе всех учеников за каждый календарный день;
- как это количество менялось под влиянием транзакций (оплат, начислений, корректирующих списаний) и уроков (списаний с баланса по мере прохождения уроков).
Также создать таблицу, где будут балансы каждого студента за каждый день.


<p>Как решала: используя подзапросы и различных условий в них мы создали табоицу в которой показан баланс студентов.

Ссылка на проект:
> https://github.com/Badretdinova/Analyst/blob/main/Курсовая%20работа%20по%20SQL

 
 <p>Выводы (итоги):<p>
<ol>
  В результате получился запрос, который собирает данные о балансах студентов за каждый прожитый ими день.
</ol>

## Контактная информация
- Email: adelka.ahmetshina@mail.ru
