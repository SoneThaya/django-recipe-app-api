# django-recipe-app-api

Recipe app api source code.

## Install dependancies

docker-compose build

## Run Server

docer-compose up

### To Run Tests

docker-compose run app sh -c "python3 manage.py test"

### Create super user

docker-compose run app sh -c "python3 manage.py createsuperuser"
