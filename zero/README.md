# Documentation


## Python - Venv
Create requirements file

pip freeze > requirements.txt


## Install
pip3 install Django==4.2.3

## Create Project

$ django-admin startproject projectname


## Note:
put code outside the document root



## Tree
- manage.py: A command-line utility that lets you interact with this Django project in various ways. You can read all the details about manage.py in django-admin and manage.py.
- The inner zero/ directory is the actual Python package for your project. Its name is the Python package name you’ll need to use to import anything inside it (e.g. mysite.urls).
- zero/__init__.py: An empty file that tells Python that this directory should be considered a Python package. If you’re a Python beginner, read more about packages in the official Python docs.
- zero/settings.py: Settings/configuration for this Django project. Django settings will tell you all about how settings work.
- zero/urls.py: The URL declarations for this Django project; a “table of contents” of your Django-powered site. You can read more about URLs in URL dispatcher.
- zero/asgi.py: An entry-point for ASGI-compatible web servers to serve your project. See How to deploy with ASGI for more details.
- zero/wsgi.py: An entry-point for WSGI-compatible web servers to serve your project. See How to deploy with WSGI for more details.

## Runserver

Run on port 8000
python manage.py runserver 

Run on custom port

python manage.py runserver 8080


## App

 python manage.py startapp polls
 
## Database sssddd

 python manage.py migrate

Add application on zero/settings

python manage.py makemigrations polls

The code is 

python manage.py sqlmigrate polls 0001