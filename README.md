﻿# ShoppingCart Back End 
## Final PHP Project
This application was developed as my final project for a PHP course, utilizing the Laravel framework. It features Google OAuth integration to provide users with a convenient login option, as well as traditional email and password authentication for account creation and login. Each user is provided with a personalized shopping cart to enhance their shopping experience.
Note: This repository contains only the backend portion of the application.

Configuration Steps
To configure the Laravel application after cloning this repository, follow these steps:

Clone the Repository:
bash
git clone [repository-url]

Navigate to the Project Directory:
bash
cd [project-directory]

Install Dependencies:
bash
composer install

Copy the Environment File:
bash
cp .env.example .env

Generate the Application Key:
bash
php artisan key:generate

Set Up the Database:
Configure your database settings in the .env file.

Run database migrations:
bash
php artisan migrate

Seed the Database (if applicable):
bash
php artisan db:seed

Serve the Application:
bash
php artisan serve

You can now access the application at http://localhost:8000.
