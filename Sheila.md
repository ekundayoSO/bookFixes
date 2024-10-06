php bin/console make:migration
php bin/console doctrine:migrations:migrate
composer require symfony/security-csrf
You need to add book.sql to the database