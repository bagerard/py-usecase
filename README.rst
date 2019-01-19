========
Overview
========

.. start-badges

.. list-table::
    :stub-columns: 1

    * - docs
      - |docs|
    * - tests
      - | |travis|
        | |codecov|
        | |landscape|
    * - package
      - | |version| |wheel| |supported-versions| |supported-implementations|
        | |commits-since|

.. |travis| image:: https://travis-ci.com/bagerard/py-usecase.svg?branch=master
    :alt: Travis-CI Build Status
    :target: https://travis-ci.com/bagerard/py-usecase

.. |codecov| image:: https://codecov.io/github/bagerard/py-usecase/coverage.svg?branch=master
    :alt: Coverage Status
    :target: https://codecov.io/github/bagerard/py-usecase

.. |landscape| image:: https://landscape.io/github/bagerard/py-usecase/master/landscape.svg?style=flat
    :target: https://landscape.io/github/bagerard/py-usecase/master
    :alt: Code Quality Status

.. |version| image:: https://img.shields.io/pypi/v/usecase.svg
    :alt: PyPI Package latest release
    :target: https://pypi.org/project/usecase

.. |commits-since| image:: https://img.shields.io/github/commits-since/bagerard/py-usecase/v0.1.0.svg
    :alt: Commits since latest release
    :target: https://github.com/bagerard/py-usecase/compare/v0.1.0...master

.. |wheel| image:: https://img.shields.io/pypi/wheel/usecase.svg
    :alt: PyPI Wheel
    :target: https://pypi.org/project/usecase

.. |supported-versions| image:: https://img.shields.io/pypi/pyversions/usecase.svg
    :alt: Supported versions
    :target: https://pypi.org/project/usecase

.. |supported-implementations| image:: https://img.shields.io/pypi/implementation/usecase.svg
    :alt: Supported implementations
    :target: https://pypi.org/project/usecase


.. end-badges

A simple library to add a Use Case layer

* Free software: MIT license

Installation
============

::

    pip install usecase

Documentation
=============


To use the project:

.. code-block:: python

    import usecase
    usecase.longest()


Development
===========

To run the all tests run::

    tox

