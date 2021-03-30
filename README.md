# Installation Steps
------------
## environment setup
cp .env.example .env

## Composer
composer install

## Generate Key
php artisan key:generate

## Setup Database
DB_HOST=localhost
DB_DATABASE=students_data
DB_USERNAME=root
DB_PASSWORD=

## Get Tables
php artisan migrate

## Run the project
php artisan serve
