<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

<p align="center">
<a href="https://github.com/laravel/framework/actions"><img src="https://github.com/laravel/framework/workflows/tests/badge.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

## About Laravel

# 🧑‍💻 Laravel Project Setup Guide

Follow these steps to clone and run the Laravel project locally for development.

---

## 🚀 Steps

1. **Clone the Repository**
    ```bash
    git clone https://github.com/mdamirkhandev/laravel-11-boilerplate
    cd laravel-11-boilerplate
    Install PHP Dependencies
    ```

composer install

npm install

npm run dev

Copy Environment File

cp .env.example .env

Update .env File

Open .env and update database credentials and app configuration:

APP_NAME=LaravelApp
APP_ENV=local
APP_KEY=
APP_DEBUG=true
APP_URL=http://localhost:8000

DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=your_database_name
DB_USERNAME=root
DB_PASSWORD=your_password
Generate Application Key

php artisan key:generate

Run Database Migrations (with seeders if needed)

php artisan migrate --seed

Start Development Server

php artisan serve

develop something amazing
