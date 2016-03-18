============
Diazo Engine
============

.. figure:: http://docs.diazo.org/en/latest/_images/diazo-concept.png
    :align: right

    Diazo Concept

Diazo allows you to apply a theme contained in a static HTML web page to a
dynamic website created using any server-side technology. With Diazo, you can
take an HTML wireframe created by a web designer and turn it into a theme for
your favourite CMS, redesign the user interface of a legacy web application
without even having access to the original source code, or build a unified
user experience across multiple disparate systems, all in a matter of hours,
not weeks.

When using Diazo, you will work with syntax and concepts familiar from working
with HTML and CSS. And by allowing you seamlessly integrate XSLT into your
rule files, Diazo makes common cases simple and complex requirements possible.


How to use diazo
================

The Diazo installation generate three scritps into
``bin`` directory from root folder project  which
are installed with the ``diazo`` egg.

diazorun
--------

The Diazo runserver is via the ``diazorun`` command
line script. To see its help output, do:

::

    $ ./bin/diazorun --help

.. tip::
    More information visit: http://docs.diazo.org/en/latest/installation.html

diazocompiler
-------------

The Diazo compiler is via the ``diazocompiler`` command
line script. To see its help output, do:

    $ ./bin/diazocompiler --help

.. tip::
    More information visit: http://docs.diazo.org/en/latest/compiler.html


diazopreprocessor
-----------------

The Preprocess RULES for Diazo is via the ``diazopreprocessor`` command
line script. To see its help output, do:

For more options just run::

    $ ./bin/diazopreprocessor --help

.. tip::
    More information visit: http://docs.diazo.org/en/latest/
