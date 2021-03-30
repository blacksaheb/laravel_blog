# Installation Steps
------------

Composer

composer install

Generate Key

php artisan key:generate

Setup Database

cp .env.example .env

DB_HOST=localhost
DB_DATABASE=students_data
DB_USERNAME=root
DB_PASSWORD=

Get Tables

php artisan migrate

Get default/initial/dummy table values

php artisan db:seed

Run the project

php artisan serve
