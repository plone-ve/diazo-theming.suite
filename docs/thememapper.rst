=====================
Thememapper for Diazo
=====================

Theme Mapper Editor
===================

This is a theme editor for Diazo. This theme editor differs
from the one found in Plone; it is a stand-alone application.
It does require Diazo to apply the XML ofc!

It is still a work in progress. No file browser, no support
for external webpages / themes. If something works; awesome.
If it doesn't; too bad.

thememapper.core
----------------

If you want to map your themes by pointing and clicking you
can use ``thememapper.core``. ``thememapper.core`` Is, like
``thememapper.diazo``, a stand-alone application and does
not require ``thememapper.diazo`` to run. For more information
please refer to the readme file of ``thememapper.core``.

How to use thememapper
----------------------

After the installation you will be able to run ``thememapper.core``
through the commandline with the ``thememapper`` script into
``bin`` directory from root folder project.

::

    $ ./bin/thememapper --static_path static/

``thememapper.core`` normally listens to port 5001. You can force
it to listen on another port by running:

::

    $ ./bin/thememapper --port <port>

For more options just run:

::

    $ ./bin/thememapper --help

.. tip::
    More information visit: https://github.com/C4RoCKeT/thememapper.core


Theme Editor with diazo
=======================

This is a stand-alone application that runs a developement
Diazo server. This means it is not fit for production!.
For more information please refer to the readme file of
``thememapper.diazo``.

thememapper_diazo
-----------------

This configuration generate the ``thememapper_diazo`` script
into ``bin`` directory from root folder project.

For more options just run::

    $ ./bin/thememapper_diazo --help

.. tip::
    More information visit: https://github.com/C4RoCKeT/thememapper.diazo
