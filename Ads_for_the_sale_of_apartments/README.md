# Исследование объявлений о продаже квартир
Для сервиса по продаже недвижимости необходимо установить параметры и определить рыночную стоимость объектов недвижимости. Данные позволят построить автоматизированную систему отслеживания аномалий и мошеннической деятельности.

## Описание данных
В качестве данных для исследования представлен архив объявлений сервиса Яндекс Недвижимость о продаже квартир в Санкт-Петербурге и соседних населённых пунктах за несколько лет. По каждой квартире есть параметры, вписанные пользователем, и параметры, полученные автоматически на основе картографических данных (например, расстояние до центра, аэропорта, ближайшего парка и водоёма).

## Цели и задачи исследования
- Подготовить данные (обработать пропуски, преобразовать типы, обработать некорректные значения и дубликаты и т.п.)
- Рассчитать параметры:
  - цену квадратного метра;
  - день недели, месяц и год публикации объявления;
  - этаж квартиры (первый, последний, другой);
  - соотношение жилой и общей площади, а также отношение площади кухни к общей
- Определять рыночную стоимость объектов недвижимости в зависимости от их параметров
- Сформулировать выводы

## Используемые библиотеки
- pandas
- matplotlib
- numpy

**Статус проекта: Завершён**
