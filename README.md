#  Book Rental Library

## Exercise 3: 

Enhance the book rental library to allow user registration and login. Implement middleware to restrict certain actions (like renting a book) to logged-in users. Focus on security aspects to protect user data and handle errors gracefully.

## Installation

- Copy `.env.example` to `.env`
- Run `composer install`
- Run `php artisan key:generate --ansi`
- Run `php artisan migrate`
- Run `php artisan db:seed --class=GenresTableSeeder`
- Run `php artisan db:seed --class=BooksTableSeeder`

## Admin Account

To create an admin account run:

`php artisan db:seed --class=AdminSeeder`

## Run Application

Run `php artisan serve` or visit project `public` directory from the browser.
