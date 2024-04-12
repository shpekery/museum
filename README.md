# Museum app

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
