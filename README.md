# Домашнє завдання #10

<b> Запуск Docker-контейнер, щоб створити сервер PostgreSQL: </b>

    docker run --name hw_project-postgres -p 5432:5432 -e POSTGRES_PASSWORD=987654321 -d postgres

<b>  Зв'язок з базою даних MongoDB: </b>

    quotes/utils.py

<b> Mіграціюz бази даних із MongoDB у Postgres для сайту реалізована кастомним скриптом: </b>

    utils/migrations.py

командою з консолі:

    py -m utils.migration

<b> Запуск сервера командою: </b>

    py manage.py runserver

<b> Посилання на сайт: </b>

     http://127.0.0.1:8000/
