# php-symfony-error-routing
A basic and lean recipe for implementing error routing in a Symfony3.

Dependencies
-
git  
php v5.5.9  
composer

To install
-
```
$ mkdir -vp php-symfony-error-routing  
$ cd php-symfony-error-routing  
$ git clone https://github.com/benjaminvickers/php-symfony-error-routing.git .  
$ composer install
```

To run in dev mode
-
```
$ php bin/console server:run
```

To run in prod mode
-
```
$ php bin/console cache:clear --env=prod  
$ php bin/console server:run --env=prod
```

To test in a browser
-
http://localhost:8000
