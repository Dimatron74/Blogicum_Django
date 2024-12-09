# Блогикум
 Вебсайт "Блогикум" на Django

## Установка

1. Установите Python (если он еще не установлен) - https://www.python.org/
2. Создайте виртуальное окружение, активируйте его, а затем установите зависимости:
    - `py -m venv .venv`
    - `source .venv/bin/activate` (либо `.venv\Scripts\Activate.ps1` на Windows)
    - `pip install -r requirements.txt`
3. Настройте базу данных в settings.py (если не желаете использовать стандартный sqlite3) и сделайте миграцию:
   ```sh
    cd blogicum
    python manage.py makemigrations
    python manage.py migrate
5. Загрузите данные (тестовые, либо свои):
    - `python manage.py loaddata db.json`
6. Создайте суперпользователя:
    - `python manage.py createsuperuser`

## Запуск

1. Запустите веб-сервер:
    - `python manage.py runserver`

## Использование

1. Откройте веб-браузер и перейдите по адресу http://localhost:8000/
2. Войдите под созданным суперпользователем на http://localhost:8000/admin/
