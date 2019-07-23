.. watchdog documentation master file, created by
   sphinx-quickstart on Tue Nov 30 00:43:58 2010.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

.. include:: global.rst.inc


Watchdog
========

Python API library and shell utilities to monitor file system events.

Works on Python 2.7 and 3.4+. If you want to use an old version of Python, you should stick with watchdog < 0.10.0.

Directory monitoring made easy with
-----------------------------------

* A cross-platform API.

* A shell tool to run commands in response to directory changes.

Get started quickly with a simple example in :ref:`quickstart`.

Easy installation
-----------------
You can use pip_ to install |project_name| quickly and easily::

    $ pip install watchdog

Need more help with installing? See :ref:`installation`.


User's Guide
============

.. toctree::
   :maxdepth: 2

   installation
   quickstart
   api
   hacking

Contribute
==========
Found a bug in or want a feature added to |project_name|?
You can fork the official `code repository`_ or file an issue ticket
at the `issue tracker`_. You can also ask questions at the official
`mailing list`_. You may also want to refer to :ref:`hacking` for information
about contributing code or documentation to |project_name|.


Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`

Licensing
---------
Licensed under the terms of the `Apache License, version 2.0`_.

Copyright 2019 ALBERT Inc.

examples/logger.py, examples/tricks.json and examples/tricks.yaml
are removed due to licensing issue.

.. links:
.. _Apache License, version 2.0: http://www.apache.org/licenses/LICENSE-2.0