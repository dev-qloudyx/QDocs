=====
QDocs
=====

QDocs is a Django app to conduct web-based docs.

Quick start
-----------

1. Add "qdocs" to your INSTALLED_APPS setting like this::

    INSTALLED_APPS = [
        ...,
        "qdocs",
    ]

2. Include the docs URLconf in your project urls.py like this::

    path("docs/", include("qdocs.urls")),

3. Run ``python manage.py migrate`` to create the qdocs models.
