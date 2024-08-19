<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

<p align="center">
<a href="https://github.com/laravel/framework/actions"><img src="https://github.com/laravel/framework/workflows/tests/badge.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

## About the Project

This project is a web application built using Laravel, Inertia.js, and React, with MySQL as the database. It aims to provide a robust foundation for building single-page applications (SPAs) with the powerful combination of Laravel's backend capabilities and React's frontend dynamicity.

## Features

- **Laravel 11.x**: A modern PHP framework with an expressive syntax.
- **Inertia.js**: Allows for building SPAs using server-side routing with React.
- **React**: A JavaScript library for building user interfaces.
- **MySQL**: A reliable relational database system for storing data.
- **Tailwind CSS**: A utility-first CSS framework for designing responsive UIs.
- **Authentication**: User authentication provided by Laravel Breeze.
- **CRUD Operations**: Basic Create, Read, Update, and Delete functionality.

## Requirements

- PHP 8.2 or higher
- Composer
- Node.js with npm
- MySQL
- Laravel CLI

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/notBobon/CekIn-App.git
cd CekIn-App
```

### 2. Install dependencies

```bash
composer install
npm install
```

### 3. Environment Setup

Copy .env.example to .env and update your database credentials:
```bash
cp .env.example .env
```
```env
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=your_database_name
DB_USERNAME=your_database_user
DB_PASSWORD=your_database_password
```

### 4. Migrate the database

Run the following command to apply migrations:
```bash
php artisan migrate
```

### 5. Build assets

Compile the frontend assets with:
```bash
npm run dev
```

### 6. Serve the application
To start the development server, run:
```bash
php artisan serve
```

### License
This project is licensed under the MIT license.
