# Django Starter

- Go to your project1 directory and create virtualenv with python 3

```
virtualenv venv -p python3
```

- Activate Virtualenv

```
source venv/bin/activate
```

- Activate venv and now use pip to install django.

```
pip install Django
```

- Start new project

```
python -m django startproject django_starter
```

- Database setup

```
 python manage.py migrate
```

- Run Your Project

```
python manage.py runserver
```

---

Running this command in console `django-admin startproject myfirstproject` will create a new django project for you, which will have another sub-folder named same as your project name. By default on creating a new project, the views.py file isn't created you have to create it manually in your project sub-folder.

To create a new app, Run `django-admin startapp myapp` which will create a new sub-folder under your parent directory which will have views.py where you can write your own custom views for your HTML templates

---

For Swagger Docs

https://github.com/axnsan12/drf-yasg?tab=readme-ov-file#id9

---
