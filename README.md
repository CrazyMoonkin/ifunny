# iFunny Crawler

https://funcodechallenge.com/

P.S. Предпочитаю термин `Crawler` термину `Spider`. Наверно, потому что не очень люблю пауков.
Гусеничный трактор – как-то поспокойнее. 😉

## Преамбула

// TODO

## Сборка и запуск

// TODO

// .env.example

### Переменные окружения

#### MongoDB

* `MONGODB_HOST` – Хост сервера MongoDB (По умолчанию `localhost`).
* `MONGODB_PORT` – Порт сервера MongoDB (По умолчанию `27017`)
* `MONGODB_DATABASE` - Имя базы данных MongoDB (По умолчанию `ifunny`).
* `MONGODB_USERNAME` – Имя пользователя MongoDB (По умолчанию `ifunny`).
* `MONGODB_PASSWORD` – Пароль пользователя MongoDB (По умолчанию `ifunny`).
* `MONGODB_AUTH_DB` – База данных аутентификации MongoDB (По умолчанию `admin`).

### Локальное окружение

Для удобства развертывания локального окружения (в целях разработки) в корневом каталоге расположен `docker-compose.yml`.

#### Запуск через терминал

```
$ docker-compose up -d
```

#### Запуск через IDEA

Если Вы используете Intellij IDEA, в репозиторий добавлена конфигурация запуска Docker-compose под именем `Local Environment`.

## Реализация

### Kotlin DSL
