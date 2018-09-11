# Blogging App 

by [Django girls](https://tutorial.djangogirls.org/en)

## commands

- Make a folder & initialise a django project
    ```shell
    django-admin startproject mysite .
    python manage.py migrate
    ```
- serve app
    ```shell
    python manage.py runserver
    ```
- create an app inside project
    ```shell
    python manage.py startapp blog
    ```
- After updating a model in the app
    ```shell
    python manage.py makemigrations blog
    python manage.py migrate blog
    ```