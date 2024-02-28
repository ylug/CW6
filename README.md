Сервис рассылок написанный на Python-django.

Для запуска проекта необходимо переименовать файл .env_sample в .env и заполнить переменные окружения своими
значениями, чтобы файл settings.py заполнился данными для подключения к БД. Или заполните данные в settings.py вручную
по шаблону: DATABASES = { 'default': { 'ENGINE': 'django.db.backends.postgresql', 'NAME': 'Django_project', 'USER': '
postgres', 'HOST': 'localhost', 'PORT': 5432, 'PASSWORD': 'user_password'