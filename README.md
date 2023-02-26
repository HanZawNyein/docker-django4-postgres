# docker-django4-postgres

    $ docker-compose up -d
    $ docker-compose up -d --build
    $ docker-compose exec web python manage.py migrate
    $ docker-compose exec web python manage.py createsuperuser
