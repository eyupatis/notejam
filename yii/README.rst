************
Notejam: Yii
************

Notejam application implemented using `Yii <http://www.yiiframework.com/>`_ framework.

Yii version: 2.0

PHP version required: 5.4+

==========================
Installation and launching
==========================

-----
Clone
-----

Clone the repo:

.. code-block:: bash

    $ git clone git@github.com:komarserjio/notejam.git YOUR_PROJECT_DIR/

-------
Install
-------

Install `composer <https://getcomposer.org/>`_

.. code-block:: bash

    $ cd YOUR_PROJECT_DIR/yii/notejam
    $ curl -s https://getcomposer.org/installer | php

Install dependencies

.. code-block:: bash

    $ cd YOUR_PROJECT_DIR/yii/notejam
    $ php composer.phar install

Create database schema

.. code-block:: bash

    $ cd YOUR_PROJECT_DIR/yii/notejam
    $ ./yii migrate


------
Launch
------

Start built-in php web server:

.. code-block:: bash

    $ cd YOUR_PROJECT_DIR/yii/notejam/web
    $ php -S localhost:8000

Go to http://localhost:8000 in your browser.

---------
Run tests
---------

Run functional tests:

.. code-block:: bash

    $ cd YOUR_PROJECT_DIR/yii/notejam/
    $ ./vendor/bin/codecept build
    $ ./vendor/bin/codecept run functional


============
Contribution
============
Do you have php/yii experience? Help the app to follow php and yii best practices.

Please send your pull requests in the ``master`` branch.
Always prepend your commits with framework name:

.. code-block:: bash

    Yii: Implemented sign in functionality

Read `contribution guide <https://github.com/komarserjio/notejam/blob/master/contribute.rst>`_ for details.

