# Интернет-магазин на Django

Сайт создавался для ИП, торгующего офисной мебелью.

## Используемые технологии

- Для хранения данных использовалась база данных __Sqlite3__. Взаимодействие с ней происходило при помощи __Django ORM__.
- Для выполнения асинхронных задач по отправке писем с информацией по заказу использовалась связка __Celery__ + __RabbitMQ__.
- Для отображения страниц сайта с нужными данными использовался встроенный в Django шаблонизатор.
