======================================
Django CmdLog - Django Command logging
======================================

Django CmdLog helps in adding the possibility to log django management commands. The log is then available in the admin interface.

Quick start
-----------

1. Add "django_cmdlog" to your ``INSTALLED_APPS`` settings like this:

.. code-block:: python

    INSTALLED_APPS = [
        ...
        'django_cmdlog',
    ]


2. Run `python manage.py makemigrations` then `python manage.py migrate` to add the columns
of `django_cmdlog` models to your database.

Requirements
------------

- python 2.7, 3.3
- django 1.10


Tested on `Django`_ 1.10.3

.. _Django: http://www.djangoproject.com/

