========
Overview
========

A VERY useful package that suppresses warnings!

* Free software: GNU Lesser General Public License v3 or later (LGPLv3+)

Installation
============

::

    pip install bekeshbiron

You can also install the in-development version with::

    pip install git+ssh://git@https://github.com/Salehbigdeli/bekeshbiron/Salehbigdeli/bekeshbiron.git@master

Documentation
=============


To use the project:

.. code-block:: python

    import bekeshbiron


Development
===========

To run all the tests run::

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
