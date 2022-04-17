=====
Usage
=====

To use django-flutterwave in a project, add it to your `INSTALLED_APPS`:

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
