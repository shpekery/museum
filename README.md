# Museum Hackaton App

Приложение для поиска, классификации и генерации описания музейных предметов по изображению.
Создано в рамках Окружного хакатона ЮФО Цифровой прорыв 2024.

## Работа с репозиторием

Склонировать репозиторий вместе с сабмодулями

```shell
git clone https://github.com/shpekery/museum.git --recursive
```

Обновить файлы в сабмодулях

```shell
git submodule update --init --remote --recursive
```

## Запуск

Сбилдить докер образ

```shell
docker compose build
```

Поднять контейнеры

```shell
docker compose up -d
```

## Для разработчиков

Добавить новый сабмодуль

```shell
git submodule add https://github.com/shpekery/museum-frontend frontend
```
