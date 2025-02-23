# larave8-multi-guards-auth

Laravel 8 Multiple Guards Authentication - admin & user  
--------------------------------------------------------

# Getting started

## Installation

Please check the official laravel installation guide for server requirements before you start. [Official Documentation](https://laravel.com/docs/8.x/installation)


Clone the repository or download the project from github

    git clone https://github.com/savitha7/larave8-multi-guards-auth.git

Install all the dependencies using composer 

    composer update

Generate a new application key

    php artisan key:generate

compile the assets so that your application's CSS file is available

    npm install
    npm run dev

Run the database migrations and seeder (**Set the database connection in .env before migrating**)

    php artisan migrate 

Start the local development server

    php artisan serve

You can now access the server at http://127.0.0.1:8000
    
**Make sure you set the correct database connection information before running the migrations**

    php artisan migrate 
    php artisan serve
    
## Admin Login/Register url

http://127.0.0.1:8000/admin/login

http://127.0.0.1:8000/admin/register

**you can change it from .env as per your need.


## Environment variables

- `.env` - Environment variables can be set in this file

***Note*** : You can quickly set the database information and other variables in this file and have the application fully working.

