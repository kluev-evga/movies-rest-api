# Drf movies

[![licence](https://img.shields.io/static/v1?label=LICENSE&message=MIT&color=97ca00&style=for-the-badge)](https://github.com/kluevEVGA/api_final_yatube/blob/master/LICENSE)
[![python version](https://img.shields.io/static/v1?label=Python&message=3.11.2&color=97ca00&style=for-the-badge)](https://python.org)
[![django version](https://img.shields.io/static/v1?label=DJANGO&message=4.1.7&color=97ca00&style=for-the-badge)](https://www.djangoproject.com/)
[![drf version](https://img.shields.io/static/v1?label=DRF&message=3.14.0&color=97ca00&style=for-the-badge)](https://www.django-rest-framework.org/)
![api version](https://img.shields.io/static/v1?label=API%20VERSION&message=1.0.0&color=97ca00&style=for-the-badge)

## О проекте

REST API backend сервис для movies.
Используется база данных postgreeSQL и django reset framework.
В проекте подключена авторизация по JWT токенам.

## Установка

Клонировать проект

```shell
git clone https://github.com/kluevEVGA/Drf-movies.git
```

Установка окружения

```shell
python3 -m venv env
```

```shell
py -m venv venv
```

Активировать окружение

```shell
.\venv\Scripts\activate
```

```shell
source env/bin/activate
```

Установка зависимостей

```shell
pip install -r requirements.txt
```

## Запуск сервера

Перейти в папку с проектом

```shell
cd .\movie\
```

Выполнить миграции

```shell
python3 manage.py migrate
```

запустить сервер

```shell
py manage.py runserver
```

## End-points
После установки сервера документация доступна по адресу:
```
swagger/
```
```
redoc/
```

## Лицензия

Распространяется по `MIT` лицензии. Для дополнительной информации
смотри: [LICENSE](https://github.com/kluevEVGA/Drf-movies/blob/master/LICENSE)
