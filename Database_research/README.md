# Исследование базы данных сервиса для чтения книг
Компания приобрела крупный сервис для чтения книг по подписке. Необходимо проанализировать базу данных. В ней — информация о книгах, издательствах, авторах, а также пользовательские обзоры книг. На основании этих данных сформулировать ценностное предложение для нового продукта.

## Описание данных

Таблица books cодержит данные о книгах:

- идентификатор книги;
- идентификатор автора;
- название книги;
- количество страниц;
- дата публикации книги;
- идентификатор издателя.

Таблица authors cодержит данные об авторах:

- идентификатор автора;
- имя автора.

Таблица publishers cодержит данные об издательствах:

- идентификатор издательства;
- название издательства;

Таблица ratings cодержит данные о пользовательских оценках книг:

- идентификатор оценки;
- идентификатор книги;
- имя пользователя, оставившего оценку;
- оценка книги.

Таблица reviews содержит данные о пользовательских обзорах на книги:

- идентификатор обзора;
- идентификатор книги;
- имя пользователя, написавшего обзор;
- текст обзора.

## Цели и задачи исследования
- Исследовать таблицы
- Сделать SQL-запросы
- Описать выводы

## Используемые библиотеки
- pandas
- sqlalchemy