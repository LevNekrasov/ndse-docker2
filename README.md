# Домашнее задание к занятию «2.5. Docker: контейнеризация приложения»

## Задание 1: контейнеризация

Контейнеризировать приложение «Библиотека»
`docker pull levnekrasov/library:v1.0.0`
`docker run -it --rm -p 80:3002 -e PORT=3002 levnekrasov/library:v1.0.0`

## Задание 2: микросервисы

Запускает «Библиотека» и "Счетчик" `docker compose up`

Открывается сайт `http://localhost:3000/books/`
