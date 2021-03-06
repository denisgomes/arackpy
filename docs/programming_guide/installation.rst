Installation
============

**arackpy** is a pure python package and runs on Windows, Linux and MacOS.

.. note:: These instructions apply to **arackpy** |version|.

**arackpy** is available `from PyPI <https://pypi.python.org/pypi/arackpy>`_.
You can install it like any other Python library:

.. code-block:: sh

    pip install arackpy

If you're installing **arackpy** into your global ``site-packages`` directory,
you might need to add ``sudo``. But you shouldn't do that; instead, create a
`venv <https://docs.python.org/3/library/venv.html>`_. Alternatively, you can
simply copy **arackpy** directly into your project folder, and use it without
any installation.

Extras
------

**arackpy** is a pure python library, however in order to use tor and proxies
the following additional packages must be installed:

.. code-block:: sh

    pip install lxml, requests, fake_useragent, pysocks

.. note:: By default, **arackpy** uses the builtin python html parser.


To install `Selenium <https://selenium-python.readthedocs.io/>`_ for dealing
with AJAX and JavaScript requests, type:


.. code-block:: sh

    pip install selenium


Running the examples
--------------------

The source code archives include examples. Archives are
`available on Github <https://github.com/denisgomes/arackpy/tree/master/examples>`_:
