![Laravel Livewire](https://picperf.io/https://laravelnews.s3.amazonaws.com/images/laravel-livewire.png)

# Laravel Livewire 

Laravel Livewire Demo is a demonstration project showcasing the usage of the Laravel Livewire package for building dynamic interfaces within Laravel applications. The project covers basic CRUD (Create, Read, Update, Delete) operations using Laravel Livewire.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Environment Variables](#environment-variables)
- [Installation](#installation)

## Introduction

Laravel Livewire is a powerful Laravel package that allows you to build interactive and dynamic user interfaces using server-side logic. It eliminates the need for extensive JavaScript code, making it an excellent choice for developers who prefer to work primarily with PHP and Laravel.



## Features

- **CRUD Operations:** Demonstrates basic CRUD operations using Laravel Livewire.
- **Eloquent Integration:** Leverages Laravel's Eloquent ORM for database interactions.
- **Blade Templating:** Integrates seamlessly with Laravel's Blade templating engine.
- **Reactive Components:** Utilizes reactive components for real-time updates without extensive JavaScript.

## Environment Variables

You need to change below following environment variables to your .env file according to your database setup

`DB_HOST`

`DB_PORT`

`DB_DATABASE`

`DB_USERNAME`

`DB_PASSWORD`

## Installation

Clone the project

```bash
  git clone https://github.com/Earth-1218/laravel-livewire.git
```

Go to the project directory

```bash
  cd laravel-livewire-demo
```

For making .env file run below command from root directory

```bash
  cp .env.example .env
```

Install dependencies

```bash
  composer install
```

Generate application key

```bash
  php artisan key:generate
```

Run database migrations

```bash
  php artisan key:generate
```

Start the server

```bash
  php artisan serve
```

## Author

**Ravi Majithiya**