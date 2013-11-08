moth: Vulnerable web application
================================

A set of vulnerable scripts which can be used for testing web application security scanners, 
teaching web application security, etc.

This software should **never be used in a production environment**.

This is a rewrite of the [PHP-based moth web application](https://github.com/andresriancho/w3af-moth).

Usage
=====

```console
$ git clone https://github.com/andresriancho/django-moth.git
$ cd django-moth
$ pip install -r requirements.txt
$ python manage.py runserver
```

Then browse to http://127.0.0.1:8000/ .
