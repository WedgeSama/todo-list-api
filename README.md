Todo List API
=============

## Install

- Clone this repository
- Run `composer install`
- Create a `.env.local` file on project root directory
- Configure your database env variable in `.env.local`
- Run `php bin/console doctrine:database:create` to create the database
- Run `php bin/console doctrine:migration:migrate` to apply the database schema
- Run `php bin/console hautelook:fixtures:load --purge-with-truncate` to populate the database with fixtures

## Run the server

`php bin/console server:run`

## License

The code used to generate this stack is release under MIT licence.
