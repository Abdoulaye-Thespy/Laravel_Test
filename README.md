## Prerequisites

# PHP, MySQL, and Apache installed. A simple installation of Xampp should take care of all these

# Composer installed

# Laravel installed, along with a basic understanding of this framework

# Postman, to test the APIs we create.

## Setup

- Clone the repo at `https://github.com/Abdoulaye-Thespy/Laravel_Test.git` on `https://github.com/  Abdoulaye-Thespy/Laravel_Test`

- Run `composer install`
- Create your Username, password, database on MySQL(on php myadmin or on MySQL command)
- Place the previous values in following variables in your .env.
         `DB_DATABASE`
         `DB_PASSWORD`
         `DB_PASSWORD`
- Run php `artisan migrate` to migrate the database.

- Run `php artisan db:seed` to create two random users needed to test this API.

- Finally run `php artisan serve` and keep it running.
- Open Postman to test this API.
- Our Endpoint for login is: `http://localhost:8000/api/login` and by using the email provided by Fakers
from our Facrotories and the given password.(phpmyadmin or MySQL command)
