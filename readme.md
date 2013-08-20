Install
====================

Git clone
---------
    git clone https://github.com/thesakhalin/yii-started

Installation#
===================

To install Composer, you just need to download the composer.phar executable.

$ curl -sS https://getcomposer.org/installer | php
For the details, see the Introduction chapter.

To check if Composer is working, just run the PHAR through php:

$ php composer.phar
This should give you a list of available commands.


Web server
---------------------
    SetEnv APPLICATION_ENV ""
        production
        development
        offline
Configure
---------
     application/config/ your web server env .php
     Sample SetEnv APPLICATION_ENV "development"
        application/config/development.php

     Configure  application/config/console.php

