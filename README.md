## Laravel UUID boilerplate

This repository shows you how to use UUID in a Laravel app.
It makes use of Ramsey UUID package that can be found [here](https://github.com/ramsey/uuid).
This repository uses Laravel 7. However if you are using a different version of Laravel, the logic remains similar. 
You can find a tutorial on this topic [here](https://medium.com/@emymbenoun/how-to-use-uuids-instead-of-auto-increment-ids-in-your-laravel-app-2e6cc045f6c1).

### How do I get set up? ###

* Clone this repo
* Run `composer install` or `composer update`
* Create a database called **your-db-name** and set the necessary user and password details
* Configure your `.env` file with the database details
* Run `php artisan migrate --seed`


### Dependencies ###

* PHP >= 7.2
* Laravel 7.*
* MySQL >= 5.7 or MariaDB >= 10.2


### Contribution guidelines ###

* Create your branch from the most up-to-date branch.
* Follow the [PSR coding standards](https://www.php-fig.org/psr/psr-12) for writing code.
* Follow the [PHPDoc standard](https://github.com/php-fig/fig-standards/blob/master/proposed/phpdoc.md) for documentation.
* Writing tests with PHP Unit test.
* Review your code before committing.

### Who do I talk to? ###

Repo owner - [Marie](https://github.com/emygeek "Marie")
