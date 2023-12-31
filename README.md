# A/B-тест. Интернет-магазин

## Данные

В наличии были следующие данные о гипотезах:
- краткое описание гипотезы
- охват пользователей по 10-балльной шкале
- влияние на пользователей по 10-балльной шкале
- уверенность в гипотезе по 10-балльной шкале
- затраты ресурсов на проверку гипотезы по 10-балльной шкале
  
Данные о заказах:
- идентификатор заказа
- идентификатор пользователя, совершившего заказ
- дата, когда был совершён заказ
- выручка заказа
- группа A/B-теста, в которую попал заказ

Данные о группах:
- дата
- группа A/B-теста
- количество пользователей в указанную дату в указанной группе A/B-теста

## Задача

Проанализировать A/B-тест. Принять решение по результатам теста: остановить тест (зафиксировать победу одной из групп) ИЛИ 
остановить тест (зафиксировать отсутствие различий между группами) ИЛИ продолжить тест. 

## Используемые библиотеки
*pandas*
*matplotlib*
*seaborn*
*math*
*scipy*
*numby*
