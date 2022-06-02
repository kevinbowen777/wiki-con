The Hypermodern Python Console Project
======================================

.. toctree::
   :hidden:
   :maxdepth: 1

   license
   reference

The example project for the
`Hypermodern Python Console <https://github.com/kevinbowen777/wiki-con>`_ GitHub repository.
The command-line interface prints random facts to your console,
using the `Wikipedia API <https://en.wikipedia.org/api/rest_v1/#/>`_.


Installation
------------

To install the Hypermodern Python project,
run this command in your terminal:

.. code-block:: console

   $ pip install wiki-con


Usage
-----

Hypermodern Python's usage looks like:

.. code-block:: console

   $ wiki_con [OPTIONS]

.. option:: -l <language>, --language <language>

   The Wikipedia language edition,
   as identified by its subdomain on
   `wikipedia.org <https://www.wikipedia.org/>`_.
   By default, the English Wikipedia is selected.

.. option:: --version

   Display the version and exit.

.. option:: --help

   Display a short usage message and exit.

Credits
-------
The code for this project is originally from the
`Hypermodern Python <https://medium.com/@cjolowicz/hypermodern-python-d44485d9d769>`_
article series.
