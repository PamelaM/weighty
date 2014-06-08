===============================
Weighty
===============================

.. image:: https://badge.fury.io/py/weighty.png
    :target: http://badge.fury.io/py/weighty

.. image:: https://pypip.in/d/weighty/badge.png
    :target: https://crate.io/packages/weighty?version=latest


Online Weight Tracking

* Free software: BSD license

Requirements
------------

* Django 1.5+
* Python 2.7
* `django-cms`_ (unstable at this time)

.. _django-cms: https://github.com/divio/django-cms

Installation
------------

Enter inside ``weighty`` folder and install all requirements inside a virtualenv:

.. code-block:: python

    pip install -r requirements/development.txt

Enter inside ``weighty`` then prepare your database (sqlite as default) and run the server:

.. code-block:: python

    python manage.py syncdb --all --settings=weighty.settings.dev
    python manage.py migrate --fake --settings=weighty.settings.dev
    python manage.py cms check --settings=weighty.settings.dev
    python manage.py runserver --settings=weighty.settings.dev

Create your first page with Django CMS admin (``http://localhost:8000/admin``)!

Features
--------

TODO