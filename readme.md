



python manage.py startapp blog создаем приложение blog

python manage.py startapp events создаем приложение events


При создании нового репозитория его название копируем из названия папки в проводнике виндовз

or push an existing repository from the command line

76 Models 

Модель - это класс. Мы должны создать здесь класс.


[Models в документации ImageField](https://docs.djangoproject.com/en/4.1/ref/models/fields/)

migrations - способ в джанго обновлять базу данных

python manage.py migrate

Прописываем в settings.py 'events.apps.EventsConfig'

python manage.py makemigrations

python -m pip install Pillow

python manage.py migrate применяем обновление

77. Admin

Нужно создать admin аккаунт 

 python manage.py createsuperuser создаем суперюзера
 Имя пишем любое

 78. Установка PostgreSQL. Windows

 [скачать postgreSQL](https://www.enterprisedb.com/downloads/postgres-postgresql-downloads)

 [как разрешить windows 10 скачивать файлы из неизвестных источников](https://www.youtube.com/watch?v=8mdWNF7jkDA)

 После установки постгрескл запустить SQL shell

 80. Подключаем PostgreSQL к проекту.

 \password postgres устанавливаем пароль юзера постгрес










