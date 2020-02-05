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
    * - package
      - | |version| |wheel| |supported-versions| |supported-implementations|
        | |commits-since|
.. |docs| image:: https://readthedocs.org/projects/pythonPackaging/badge/?style=flat
    :target: https://readthedocs.org/projects/pythonPackaging
    :alt: Documentation Status

.. |travis| image:: https://api.travis-ci.org/arunmastermind/pythonPackaging.svg?branch=master
    :alt: Travis-CI Build Status
    :target: https://travis-ci.org/arunmastermind/pythonPackaging

.. |appveyor| image:: https://ci.appveyor.com/api/projects/status/github/arunmastermind/pythonPackaging?branch=master&svg=true
    :alt: AppVeyor Build Status
    :target: https://ci.appveyor.com/project/arunmastermind/pythonPackaging

.. |requires| image:: https://requires.io/github/arunmastermind/pythonPackaging/requirements.svg?branch=master
    :alt: Requirements Status
    :target: https://requires.io/github/arunmastermind/pythonPackaging/requirements/?branch=master

.. |codecov| image:: https://codecov.io/github/arunmastermind/pythonPackaging/coverage.svg?branch=master
    :alt: Coverage Status
    :target: https://codecov.io/github/arunmastermind/pythonPackaging

.. |version| image:: https://img.shields.io/pypi/v/mydemo.svg
    :alt: PyPI Package latest release
    :target: https://pypi.org/project/mydemo

.. |wheel| image:: https://img.shields.io/pypi/wheel/mydemo.svg
    :alt: PyPI Wheel
    :target: https://pypi.org/project/mydemo

.. |supported-versions| image:: https://img.shields.io/pypi/pyversions/mydemo.svg
    :alt: Supported versions
    :target: https://pypi.org/project/mydemo

.. |supported-implementations| image:: https://img.shields.io/pypi/implementation/mydemo.svg
    :alt: Supported implementations
    :target: https://pypi.org/project/mydemo

.. |commits-since| image:: https://img.shields.io/github/commits-since/arunmastermind/pythonPackaging/v0.0.0.svg
    :alt: Commits since latest release
    :target: https://github.com/arunmastermind/pythonPackaging/compare/v0.0.0...master



.. end-badges

An example package. Generated with cookiecutter-pylibrary.

* Free software: BSD 2-Clause License

Installation
============

::

    pip install mydemo

You can also install the in-development version with::

    pip install https://github.com/arunmastermind/pythonPackaging/archive/master.zip


Documentation
=============


https://pythonPackaging.readthedocs.io/


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
