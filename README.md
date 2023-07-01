# Laravel WebSockets

A WebSocket server built with Laravel WebSockets.

## Getting started

### Prerequisites
```bash
php -v
composer -V
mysql -V
```

### Installing

Clone this repo.

```bash
git clone https://github.com/sc27kr/laravel-websockets.git
```

Copy .env.

```bash
cd laravel-websockets
cp .env.example .env
```

Install the project dependencies.

```bash
composer i
npm i
```

Create database and migrate.

```bash
mysql -uroot -p -e "CREATE DATABASE laravel"
php artisan migrate
```

Set the application key.

```bash
php artisan key:generate
```

Serve WebSockets on the PHP development server.

```
php artisan serve --port=8001
php artisan websockets:serve
```

List all registered routes.

```bash
php artisan route:list
```

Enjoy! [http://localhost:8001/panel](http://localhost:8001/panel)

## Built with

* PHP
* Laravel
* Laravel WebSockets
