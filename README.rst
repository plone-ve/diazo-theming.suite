Diazo theming suite
====================

The idea with this buildout configuration is show how install
a Plone latest version, for integrate with Diazo Theming for
a Django application, Joomla, Drupal and Wordpress CMS with
Plone in the same GUI. Using thememapper as a Diazo theming
editor external.

Features
--------

Diazo theming suite includes some Plone products and configurations like these:

 - `diazo`_ as a Diazo theming server.

 - `thememapper.core`_ as a Diazo theming editor external.

Development installation
------------------------

To get a basic development installation running follow the steps below: ::

    $ git clone https://github.com/plone-ve/diazo-theming.suite.git
    $ cd diazo-theming.suite
    $ python bootstrap.py
    $ ./bin/buildout -vvvvvvvvN

How to use diazo
-----------------
    
For more options just run::

    $ ./bin/diazorun --help

TODO

How to use thememapper
-----------------------

After the installation you will be able to run thememapper.core through the commandline::

    $ ./bin/thememapper

Thememapper.core normally listens to port 5000. You can force it to listen on another port by running::
    
    $ ./bin/thememapper --port <port>
    
For more options just run::

    $ ./bin/thememapper --help

How to use Wordpress
---------------------

For access to Wordpress administration panel use the follow url address: 

TODO

How to use Joomla! 
-------------------

For access to Joomla! administration panel use the follow url address:

TODO

How to use Drupal
------------------

For access to Drupal administration panel use the follow url address:

TODO


Support
=======

If you run into any issues trying to get this to work, please, add an
issue to the `tracker here`_ on this github project.

Collaborations
==============

Really thanks to :

* Brandon Tilstra aka C4RoCKeT

Original Author
----------------

* Leonardo J .Caballero G. aka macagua

Impressive collaborations
-------------------------

* Full name aka username

For an updated list of all contributors visit the following URL: https://github.com/plone-ve/diazo-theming.suite/contributors

.. _tracker here: https://github.com/plone-ve/diazo-theming.suite/issues
.. _diazo: http://www.diazo.org
.. _thememapper.core: https://github.com/plone-ve/thememapper.core