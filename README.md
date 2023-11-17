# Laravel Cheat Sheet
<p align="center">
  <img src="https://laravel.com/assets/img/components/logo-laravel.svg" alt="Laravel Logo" width="200"/>
</p>
Welcome to the Laravel Cheat Sheet repository! This collection of frequently used command-line snippets is designed to be your quick reference guide when working with Laravel, one of the most popular PHP web application frameworks.

## Contents
### Installation
### Artisan Commands
### Database
### Eloquent ORM
### Routes
### Middleware
### Controllers
### Views
### Testing
### Installation
### bash
### Copy code

### Install Laravel using Composer
`composer create-project --prefer-dist laravel/laravel projectName`

# Navigate to your project directory
`cd projectName`

# Start the development server
php artisan serve
Save to grepper
Artisan Commands
Migrations
bash
Copy code
# Run pending migrations
php artisan migrate

# Rollback the last database migration
php artisan migrate:rollback

# Create a new migration file
php artisan make:migration CreateTableName
Save to grepper
Seeders
bash
Copy code
# Run database seeders
php artisan db:seed

# Generate a seeder class
php artisan make:seeder SeederClassName
Save to grepper
Tinker (Interactive Shell)
bash
Copy code
# Enter the Tinker interactive shell
php artisan tinker

# Execute arbitrary PHP code
Save to grepper
Database
Eloquent Models
bash
Copy code
# Create a new Eloquent model
php artisan make:model ModelName

# Create a new migration and model
php artisan make:model ModelName -m
Save to grepper
Database Operations
bash
Copy code
# Create a new database migration
php artisan make:migration create_table_name

# Rollback the last database migration
php artisan migrate:rollback

# Refresh the database and run all seeders
php artisan migrate:refresh --seed
Save to grepper
For more commands and details, explore the sections mentioned above. Feel free to contribute by opening an issue or submitting a pull request!

Happy coding with Laravel! 🚀✨
