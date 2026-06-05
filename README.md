# Электронный журнал на Flask

Dockerized-приложение для работы с электронным журналом. В проекте есть Flask API, PostgreSQL со схемой, seed-данными, views и stored procedures, а также pgAdmin для просмотра базы.

## Стек

- Python
- Flask
- PostgreSQL
- pgAdmin
- Docker Compose

## Возможности

- Получение справочников групп, предметов и преподавателей
- Просмотр студентов по группам
- Работа с экзаменами и сессионными оценками
- CRUD endpoints для основных сущностей
- Инициализация БД SQL-скриптами
- Схема базы в формате Draw.io

## Запуск

```bash
docker compose up --build
```

После запуска:

| Компонент | URL |
| --- | --- |
| Flask API | http://localhost:5000 |
| pgAdmin | http://localhost:5050 |

Демо-настройки PostgreSQL и pgAdmin находятся в `docker-compose.yml`.

## Структура

```text
app/               Flask-приложение
db/                Dockerfile и SQL-скрипты БД
docker-compose.yml локальное окружение
schema.drawio      схема базы данных
reqs.xsh           примеры HTTP-запросов
```

## Для портфолио

Проект демонстрирует backend-сервис на Flask с PostgreSQL, процедурной логикой в БД и контейнеризированным окружением.

