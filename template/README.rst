django-{{ app_name }}
========================

.. image:: https://travis-ci.org/littlepea/django-{{ app_name }}.png?branch=master
    :target: http://travis-ci.org/littlepea/django-{{ app_name }}

Welcome to the documentation for django-{{ app_name }}!

Credits
-------

* Project on GitHub: `littlepea/django-{{ app_name }} <https://github.com/littlepea/django-{{ app_name }}/>`_
* `Documentation on Read The Docs <https://django-{{ app_name }}.readthedocs.org/>`_
* Maintained by `Evgeny Demchenko <https://github.com/littlepea>`_

Installation
------------

1. Install `django-{{ app_name }}` package::

    pip install django-{{ app_name }}

2. Add `{{ app_name }}` to INSTALLED_APPS in settings.py::

    INSTALLED_APPS = (
        ...
        '{{ app_name }}',
        ...
    )

3. Add `{{ app_name }}.urls` to urls.py::

    urlpatterns = patterns('',
        ...
        url(r'^{{ app_name }}/', include('{{ app_name }}.urls')),
        ...
    )

4. Customize configuration::

    SETTING_NAME = 'value'

Configuration
-------------

SETTING_NAME (required)
^^^^^^^^^^^^^^^^^^^^^^^

Setting description.


Running the Tests
------------------------------------

You can run the tests with via::

    python setup.py test

or::

    python {{ app_name }}/tests/runtests.py
