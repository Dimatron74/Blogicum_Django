# Блогикум
 Вебсайт "Блогикум" на Django

## Установка

1. Установите Python (если он еще не установлен) - https://www.python.org/
2. Установите pip - https://pip.pypa.io/en/stable/installing/
3. Установите virtualenv - https://pypi.python.org/pypi/virtualenv
4. Создайте виртуальное окружение, активируйте его, а затем установите зависимости:
    - `virtualenv blogicum-env`
    - `source blogicum-env/bin/activate` (либо `blogicum-env\Scripts\activate` на Windows)
    - `pip install -r requirements.txt`
5. Создайте settings.py, основанный на settings.py.template
6. Создайте базу данных и сделайте миграцию:
    - `python manage.py makemigrations`
    - `python manage.py migrate`
7. Загрузите данные:
    - `python manage.py loaddata db.json`
8. Создайте администратора:
    - `python manage.py createsuperuser`

## Запуск

1. Запустите веб-сервер:
    - `python manage.py runserver`

## Использование

1. Откройте веб-браузер и перейдите по адресу http://localhost:8000/
2. Войдите под администратором

