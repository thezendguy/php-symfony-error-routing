# php-symfony-error-routing
A basic and lean recipe for implementing error routing in a Symfony3.

Run this in different modes (dev and prod) to use the different template files. In
<strong><code>dev</code></strong> mode, the <strong><code>exception</code></strong> 
templates are used. In <strong><code>prod</code></strong> mode, the <strong><code>error</code></strong> templates are used.

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
