=============================
django-flutterwave
=============================

.. image:: https://badge.fury.io/py/django-flutterwave.svg
    :target: https://badge.fury.io/py/django-flutterwave

.. image:: https://travis-ci.org/WilliamOtieno/django-flutterwave.svg?branch=master
    :target: https://travis-ci.org/WilliamOtieno/django-flutterwave

.. image:: https://codecov.io/gh/WilliamOtieno/django-flutterwave/branch/master/graph/badge.svg
    :target: https://codecov.io/gh/WilliamOtieno/django-flutterwave

Flutterwave Payments for Django Projects

Documentation
-------------

The full documentation is at https://django-flutterwave.readthedocs.io.

Quickstart
----------

Install django-flutterwave::

    pip install django-flutterwave

Add it to your `INSTALLED_APPS`:

.. code-block:: python

    INSTALLED_APPS = (
        ...
        'django_flutterwave.apps.DjangoFlutterwaveConfig',
        ...
    )

Add django-flutterwave's URL patterns:

.. code-block:: python

    from django_flutterwave import urls as django_flutterwave_urls


    urlpatterns = [
        ...
        url(r'^', include(django_flutterwave_urls)),
        ...
    ]

Features
--------

* TODO

Running Tests
-------------

Does the code actually work?

::

    source <YOURVIRTUALENV>/bin/activate
    (myenv) $ pip install tox
    (myenv) $ tox


Development commands
---------------------

::

    pip install -r requirements_dev.txt
    invoke -l


Credits
-------

Tools used in rendering this package:

*  Cookiecutter_
*  `cookiecutter-djangopackage`_

.. _Cookiecutter: https://github.com/audreyr/cookiecutter
.. _`cookiecutter-djangopackage`: https://github.com/pydanny/cookiecutter-djangopackage
