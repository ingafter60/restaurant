# Section 1: Introduction

## 1. Introduction

# Section 2: Create Our Restaurant Project

## 2. Creating Our Restaurant Project

2. Creating Our Restaurant Project

1.1. Create Django Project

G:\Django\Django_Projects
λ python -m virtualenv _env36214
λ cd _env36214
λ Scripts\activate
(_env36214) λ pip install django==2.1.4
(_env36214) λ pip freeze
Django==2.1.4
pytz==2019.2
G:\Django\Django_Projects\_env36214
(_env36214) λ cd ..
G:\Django\Django_Projects
(_env36214) λ md restaurant
G:\Django\Django_Projects
(_env36214) λ cd restaurant\
G:\Django\Django_Projects\restaurant
(_env36214) λ django-admin startproject _src .

1.2 Create superuser

(_env36214) λ python manage.py migrate
(_env36214) λ python manage.py createsuperadmin

1.3 Run the server

(_env36214) λ python manage.py runserver

## 3. Creating Our Meals App

> (_env36214) λ python manage.py startapp app_meals
> registering app_meals to the project
> install Pillow for images 'pip install Pillow'
> create Meals model
> add meals
> showing the meals name to admin
