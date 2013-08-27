Install
====================

Git clone
---------
    git clone git@github.com:sakhalin/yii-starting.git

Installation#
===================

To install Composer, you just need to download the composer.phar executable.

    $ curl -sS https://getcomposer.org/installer | php
For the details, see the Introduction chapter.


This should give you a list of available commands.

    php composer.phar install

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

