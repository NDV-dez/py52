# Создание виртуального окружения

1. Создайте рабочую дииректорию
2. Перейдите в созданную директорию через cmd или bash
3. Выполните команду "python -m venv env"
4. Перейдите в папку "./<your-project-name>/env/Scripts" и выполните команду ("activate" cmd| "source activate" bash) **ИЛИ** выполните команду ("env/Scripts/activate" cmd | 'source env/Scripts/activate' bash);
5. Вернитесь на уровень проекта.

# Создание Django проекта

1. Выполните команду "pip install django";
2. Выполните команду "django-admin startproject <your-project-name>";
3. После выполнения команды из пункта 2, в вашей папке с проектом будет создана папка "<your-project-name>". Зайдите в нее и выполните команду ("manage.py startapp <your-app-name>" cmd | "python manage.py startapp <your-app-name>" bash);
4. Для проверки корректности создания проекта выполните команду ("manage.py runserver" cmd | "python manage.py runserver" bash).