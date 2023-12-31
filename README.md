# Kittygram
## Описание проекта

Kittygram - социальная сеть для обмена фотографиями любимых питомцев. Это полностью рабочий проект, который состоит из бэкенд-приложения на Django и фронтенд-приложения на React.

[![Workflow Status](https://github.com/dariazueva/kittygram_final/actions/workflows/main.yml/badge.svg)](https://github.com/dariazueva/kittygram_final/actions/workflows/main.yml)

### Основной функционал проекта:

- Регистрация новых пользователей
- Вход и выход зарегистрированных пользователей
- Просмотр постов с котиками с их фотками
- Создание, редактирование и удаление постов с котиками
- Добавление и изменение достижений котиков

### Основной стек технологий проекта:

django, gunicorn, nginx, docker, react, github actions, node.js, postgresql, djando rest 

### Как развернуть проект:

#### Клонируйте репозиторий.
```bash
git clone git@github.com:dariazueva/kittygram_final.git
```
#### Перейдите в директорию бэкенд-приложения проекта.
```bash
cd kittygram_final/backend/
```
#### Создайте виртуальное окружение.
```bash
python3 -m venv venv
```
#### Активируйте виртуальное окружение.
```bash
source venv/bin/activate
```
#### Установите зависимости.
```bash
pip install -r requirements.txt
```
#### В папке kittygram/ создайте файл .env по образцу:
```bash
POSTGRES_USER=django_user
POSTGRES_PASSWORD=mysecretpassword
POSTGRES_DB=django
DB_HOST=db
DB_PORT=5432
```

## Автор
Зуева Дарья Дмитриевна
Github https://github.com/dariazueva/
