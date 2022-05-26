# Lab 28

## Django REST Framework and Docker

### Author

- Ella Svete
- I worked on this with help from the class demo

### How to Run this Application

- python3 -m venv .venv
- source .venv/bin/activate
- pip install django
- pip install djangorestframework
- django-admin startproject snack_tracker_project
- python manage.py migrate
- python manage.py runserver
- python manage.py startapp snacks
- Make TUV and add to settings
- python manage.py makemigrations snacks
- python manaage.py createsuperuser
- python manage.py runserver

- docker compose up
- docker compose start

### Tests

- to run tests import the class Snacks
- import django.test import TestCase
- python manage.py test to run tests

- I referenced the tests provided in today's demo

### Overview

- I appreciate the repetition with the labs this week. I am curious how to install auto fill things for django because it so much repetitive typing in each file!