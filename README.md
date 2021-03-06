zf2-cqrs-sample
=======================

Introduction
------------
This is a simple TODO application using [ZF2](http://framework.zend.com/) and [malocher/cqrs-esb](https://github.com/malocher/cqrs-esb). This application is meant to be used as a starting place for those
looking to get their feet wet with CQRS and an Enterprise Service Bus in a ZF2 Project.


Installation
------------

Using Git and  Composer (recommended)
----------------------------

clone the repository and manually invoke `composer` using the shipped
`composer.phar`:

    cd my/project/dir
    git clone git://github.com/malocher/zf2-cqrs-sample.git
    cd zf2-cqrs-sample
    php composer.phar self-update
    php composer.phar install

Virtual Host
------------
Afterwards, set up a virtual host to point to the public/ directory of the
project and you should be ready to go!

Alternatively — if you are using PHP 5.4 or above — you may start the internal PHP cli-server in the public
directory:

    cd public
    php -S 0.0.0.0:8080 index.php

This will start the cli-server on port 8080, and bind it to all network
interfaces.

Documentation
-------------
We've placed comments and explanations everywhere in the sourcecode. Use Github to
browse to the code and also check out the various README.md files in the sub directories.

A good starting point is the application module configuration. 
You can find it in [module/Application/config/module.config.php](https://github.com/malocher/zf2-cqrs-sample/blob/master/module/Application/config/module.config.php).
