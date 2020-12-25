Установка виртуального окружения
====================================
python3 -m venv venv

Активация виртуального окружения
====================================
source venv/bin/activate

pip install Django

django-admin startproject mysite

python manage.py runserver

python manage.py startapp news

pip freeze > requirements. txt

pip install -r requirements.txt

python manage.py makemigrations

python manage.py migrate

python manage.py createsuperuser

  {
    "name": "Django",
    "type": "python",
    "request": "launch",
    "stopOnEntry": false,
    "pythonPath": "${config.python.pythonPath}",
    "program": "${workspaceRoot}/manage.py",
    "args": [
        "runserver",
        "--no-color",
        "--noreload"
    ],


