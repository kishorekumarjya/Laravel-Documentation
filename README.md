# Installing Laravel
Via Laravel Installer
First, download the Laravel installer using Composer:

composer global require laravel/installer

Once installed, the laravel new command will create a fresh Laravel installation in the directory you specify. For instance, laravel new blog will create a directory named blog containing a fresh Laravel installation with all of Laravel's dependencies already installed:

laravel new blog

Via Composer Create-Project
Alternatively, you may also install Laravel by issuing the Composer create-project command in your terminal:

composer create-project --prefer-dist laravel/laravel:^7.0 blog

Local Development Server

php artisan serve

=======
 








# Debugbar for Laravel
https://github.com/barryvdh/laravel-debugbar
Require this package with composer. It is recommended to only require the package for development.
composer require barryvdh/laravel-debugbar --dev

