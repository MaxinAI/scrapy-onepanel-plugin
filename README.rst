========
Overview
========

.. start-badges

.. list-table::
    :stub-columns: 1

    * - tests
      - |
        |
    * - package
      - | |commits-since|

.. |commits-since| image:: https://img.shields.io/github/commits-since/mikheillomidze/MaxinAI/scrapy-onepanel-plugin/v0.0.0.svg
    :alt: Commits since latest release
    :target: https://github.com/MaxinAI/scrapy-onepanel-plugin/compare/v0.0.0...master



.. end-badges

 A Scrapy plugin to distribute crawling on Onepanel.

* Free software: MIT license

Installation
============

::

    pip install scrapy-onepanel-plugin

You can also install the in-development version with::

    pip install https://github.com/MaxinAI/scrapy-onepanel-plugin/archive/master.zip


Documentation
=============


To use the project:

.. code-block:: python

    import scrapy_onepanel_plugin
    scrapy_onepanel_plugin.longest()


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
