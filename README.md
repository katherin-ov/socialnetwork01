# Проект SocialNetwork.01

[![pytest](https://img.shields.io/badge/-pytest-464646?style=for-the-badge&logo=pytest)](https://docs.pytest.org/en/6.2.x/)
![Django](https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=Django)
![HTML5](https://img.shields.io/badge/HTML5-34F26?style=for-the-badge&logo=Html5&logoColor=white)
[![CSS](https://img.shields.io/badge/-CSS-464646?style=for-the-badge&logo=css3)](https://en.wikipedia.org/wiki/CSS)
![Python](https://img.shields.io/badge/python-black?style=for-the-badge&logo=python&logoColor=blue)
![Git](https://img.shields.io/badge/Git-black?style=for-the-badge&logo=Git&logoColor=red)
## Описание

SocialNetwork - это социальная сеть с авторизацией, персональными лентами, комментариями и подписками на авторов статей.

## Функционал

* Создано и зарегистрировано приложение Posts;
* Подключена база данных;
* Десять последних записей выводятся на главную страницу;
* В админ-зоне доступно управление объектами модели ```Post```. Можно публиковать новые записи, редактировать и удалять существующие;
* Пользователь может перейти на страницу любого сообщества, где отображаются десять последних публикаций из этой группы.

## Установка

1. Клонировать репозиторий:

    ```python
    git clone https://github.com/egorcoders/hw02_community.git
    ```

2. Перейти в папку с проектом:

    ```python
    cd hw02_community/
    ```

3. Установить виртуальное окружение для проекта:

    ```python
    python -m venv venv
    ```

4. Активировать виртуальное окружение для проекта:

    ```python
    # для OS Lunix и MacOS
    source venv/bin/activate

    # для OS Windows
    source venv/Scripts/activate
    ```

5. Установить зависимости:

    ```python
    python3 -m pip install --upgrade pip
    pip install -r requirements.txt
    ```

6. Выполнить миграции на уровне проекта:

    ```python
    cd yatube
    python3 manage.py makemigrations
    python3 manage.py migrate
    ```

7. Запустить проект локально:

    ```python
    python3 manage.py runserver

    # адрес запущенного проекта
    http://127.0.0.1:8000
    ```
### __Технологии__
* Python3
* Flake8
* pytest==6.2.5
* HTML5
* Django==2.2.9

### __Автор__
[Екатерина Новикова](https://github.com/katherin-ov)
