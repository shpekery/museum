# Museum Hackaton App

Приложение для поиска, классификации и генерации описания музейных предметов по изображению.
Создано в рамках Окружного хакатона ЮФО Цифровой прорыв 2024.

# ВАЖНО!

В этом репозитории могут отображаться неактуальные версии сервисов

Ссылки на актуальные версии:

- Бекенд: https://github.com/shpekery/museum-backend
- Фронтенд: https://github.com/shpekery/museum-frontend
- ML: https://github.com/shpekery/museum-ml

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

Файл `.env.example` переименовать в `.env` и обновить в нем переменную окружения `ML_API_URI` (ссылка на API ML сервиса)

Сбилдить докер образы

```shell
docker compose build
```

Поднять контейнеры

```shell
docker compose up -d
```

Запустятся фронтенд и бекенд, ML сервис поднимается отдельно

## Для разработчиков

Добавить новый сабмодуль

```shell
git submodule add https://github.com/shpekery/museum-frontend frontend
```
