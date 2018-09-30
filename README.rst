========
Overview
========

.. start-badges

.. list-table::
    :stub-columns: 1

    * - docs
      - |docs|
    * - tests
      - | |travis| |appveyor| |requires|
        | |codecov|
        | |landscape|
    * - package
      - | |version| |wheel| |supported-versions| |supported-implementations|
        | |commits-since|

.. |docs| image:: https://readthedocs.org/projects/django-smarter-settings/badge/?style=flat
    :target: https://readthedocs.org/projects/django-smarter-settings
    :alt: Documentation Status


.. |travis| image:: https://travis-ci.org/techdragon/django-smarter-settings.svg?branch=master
    :alt: Travis-CI Build Status
    :target: https://travis-ci.org/techdragon/django-smarter-settings

.. |appveyor| image:: https://ci.appveyor.com/api/projects/status/github/techdragon/django-smarter-settings?branch=master&svg=true
    :alt: AppVeyor Build Status
    :target: https://ci.appveyor.com/project/techdragon/django-smarter-settings

.. |requires| image:: https://requires.io/github/techdragon/django-smarter-settings/requirements.svg?branch=master
    :alt: Requirements Status
    :target: https://requires.io/github/techdragon/django-smarter-settings/requirements/?branch=master

.. |codecov| image:: https://codecov.io/github/techdragon/django-smarter-settings/coverage.svg?branch=master
    :alt: Coverage Status
    :target: https://codecov.io/github/techdragon/django-smarter-settings

.. |landscape| image:: https://landscape.io/github/techdragon/django-smarter-settings/master/landscape.svg?style=flat
    :target: https://landscape.io/github/techdragon/django-smarter-settings/master
    :alt: Code Quality Status

.. |version| image:: https://img.shields.io/pypi/v/django-smarter-settings.svg
    :alt: PyPI Package latest release
    :target: https://pypi.python.org/pypi/django-smarter-settings

.. |commits-since| image:: https://img.shields.io/github/commits-since/techdragon/django-smarter-settings/v0.1.0.svg
    :alt: Commits since latest release
    :target: https://github.com/techdragon/django-smarter-settings/compare/v0.1.0...master

.. |wheel| image:: https://img.shields.io/pypi/wheel/django-smarter-settings.svg
    :alt: PyPI Wheel
    :target: https://pypi.python.org/pypi/django-smarter-settings

.. |supported-versions| image:: https://img.shields.io/pypi/pyversions/django-smarter-settings.svg
    :alt: Supported versions
    :target: https://pypi.python.org/pypi/django-smarter-settings

.. |supported-implementations| image:: https://img.shields.io/pypi/implementation/django-smarter-settings.svg
    :alt: Supported implementations
    :target: https://pypi.python.org/pypi/django-smarter-settings


.. end-badges

A smarter Django settings library for Python 3.7 and newer.

* Free software: MIT license

Installation
============

::

    pip install django-smarter-settings

Documentation
=============


https://django-smarter-settings.readthedocs.io/


Development
===========

To run the all tests run::

    tox

Note, to combine the coverage data from all the tox environments run:

.. list-table::
    :widths: 10 90
    :stub-columns: 1

    - - Windows
      - ::

            set PYTEST_ADDOPTS=--cov-append
            tox

    - - Other
      - ::

            PYTEST_ADDOPTS=--cov-append tox
