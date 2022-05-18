composer require doctrine/orm
composer require doctrine -> x (answer)

change DATABASE_NAME in symfony/mamp/.env ()

web/.env:

- DATABASE_URL=mysql://root:lionPass@db:3306/reactCRUD?serverVersion=5.7

<!-- docker-compose up --build (inside parent dir - symfony-mamp) -->

composer require symfony/maker-bundle --dev

php bin/console make:entity (create table)

docker-compose up --build (inside parent dir - symfony-mamp)

php bin/console make:migration
(this should not work)
-> restart docker symfony-mamp
open docker cli (www), cd web, then run:
php bin/console make:migration

next run:
php bin/console doctrine:migrations:migrate
(Database should be now visible in MyPHP admin)

```web
php bin/console make:controller ProjectController
```

composer require symfony/webpack-encore-bundle

npm run watch (creates build folder in public)

(create main.js in assets)
