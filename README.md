# Laravel 8 + Jetstream + Livewire + Tailwind + Windmill

## Requirements

- PHP version 8
- Laravel installer
- Composer
- Npm installer

## Project Details
- Project : WA Biz
- Version : v1.0
- Author : Nazrul Hanif / Ahmad Miqdad
- Date Created : 20210919

## Installation

```
# Clone the repository from GitHub and open the directory:
git clone https://github.com/lordnaz/wabiz.git

# cd into your project directory
cd larawind

# install composer and npm packages
composer install
npm install && npm run dev

# Start prepare the environment:
cp .env.example .env // setup database credentials
php artisan key:generate
php artisan migrate
php artisan storage:link

# Run your server
php artisan serve

