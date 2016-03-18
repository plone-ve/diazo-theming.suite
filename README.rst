Diazo theming suite
===================

The idea with this buildout configuration is show how install
a Plone latest version, for integrate with Diazo Theming for
a Django application, Joomla, Drupal and Wordpress CMS with
Plone in the same GUI. Using thememapper as a Diazo theming
editor external.

Features
--------

Diazo theming suite includes some products and configurations like these:

 - `diazo`_ as a Diazo theming server.

 - `thememapper.core`_ as a Diazo theming editor external.

 - `composer`_ as a Dependency Manager for PHP.

Also this suite support for severals CMS / Webapps like these:

 - `Wordpress`_ as a CMS PHP based for Blog.

 - `Drupal`_ as a CMS PHP based for Community Website.

 - `Joomla`_ as a CMS PHP based for Personal Website.

 - `Plone`_ as a CMS Python based for Intranet Website.

 - `Django`_ as a Python based Application for simple Webapp.

Development installation
------------------------

To get a basic development installation running follow the steps below: ::

    $ git clone https://github.com/plone-ve/diazo-theming.suite.git
    $ cd diazo-theming.suite
    $ python bootstrap.py
    $ ./bin/buildout -vvvvvvvvN
    $ ./bin/buildout install diazotools
    $ ./bin/buildout install composer-run

How use this project
====================

Please check the docs directory for more details about this project.

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
.. _composer: https://getcomposer.org/
.. _thememapper.core: https://github.com/plone-ve/thememapper.core
.. _Wordpress: https://wordpress.org
.. _Drupal: https://drupal.org
.. _Joomla: https://www.joomla.org
.. _Plone: https://plone.org
.. _Django: https://www.djangoproject.com/
