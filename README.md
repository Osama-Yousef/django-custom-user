# Lab: 29 - Django Custom User



## Feature Tasks and Requirements
* create Django application from scratch that has a custom user model named CustomUser
* Custom user should use email instead of username for signup / login
* Application should work with Django Admin

----------------------------------------------------------------------------------------

## Configuration


```
mkdir django-custom-user
cd django-custom-user
poetry init -n
poetry add django
poetry add --dev black
poetry shell
code .
django-admin startproject custom_user_project .
python manage.py startapp users 
python manage.py runserver
```