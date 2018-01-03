# Django Projects 

## Libraries to look into

- django-rest
- django-cms
- django-rest-auth

## Quickstart

Getting postgress database up
```
docker run -d --name pgd postgres:10 --port 5432:5432
```

Getting a python 3 environment up
```
python3 -m venv venv
```

Some command lines to quickly go through
```
django-admin startproject mysite
python manage.py runserver 0:8000
python manage.py startapp polls

python manage.py make migrations polls
python manage.py migrate

python manage.py createsuperuser

```
