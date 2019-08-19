# Python/Django CRUD Base

## Description

This is a CRUD base for Python/Django. It relies only in HTML forms and submits to persist data.

## Installation

Clone repository:

```
> clone ...
```

Create virtual environment:

```
> virtualenv env
```

Activate environment:

(Windows)
```
> .\env\Scripts\activate
```

(Linux/MAC)
```
> source ./env/bin/activate
```

Install requirements:

```
(env) > pip install -r requirements.txt
```

## Finish configuration

Run the following commands to finish the configurarion:

```
(env) > python ./manage.py makemigrations
(env) > python ./manage.py migrate
(env) > python ./manage.py createsuperuser
(env) > python ./manage.py collectstatic
```

## Sample quickstart

Finally run the server:

```
(env) > python manage.py runserver
```

And navigate to ```movies``` App address:

```
http://localhost:8000/movies/
```