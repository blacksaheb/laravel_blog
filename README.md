# Installation Steps
------------

##Composer

composer install

##Generate Key

php artisan key:generate

##Setup Database

cp .env.example .env

DB_HOST=localhost
DB_DATABASE=students_data
DB_USERNAME=root
DB_PASSWORD=

##Get Tables

php artisan migrate

##Run the project

php artisan serve
