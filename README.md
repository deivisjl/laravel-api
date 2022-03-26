<h1 align="center">
   Laravel - API
</h1>
<p align="center">
    <a href="https://laravel.com/"><img src="https://img.shields.io/badge/Laravel-v8-success?style=flat-square&logo=Laravel" alt="deivisjl-laravel"/></a>
    <a href="https://laravel.com/docs/8.x/passport/"><img src="https://img.shields.io/badge/Passport-v10.3-success?style=flat-square&logo=Laravel&logoColor=#000000" alt="deivisjl-vuetify"/></a>
</p>
<p align="center">
    <a href="#"><img src="https://img.shields.io/github/followers/deivisjl?style=social" alt="deivisjl-followers"/></a>
    <a href="#"><img src="https://img.shields.io/github/stars/deivisjl/laravel-api?style=social" alt="deivisjl-stars"/></a>
    <a href="#"><img src="https://img.shields.io/github/forks/deivisjl/laravel-api?style=social" alt="deivisjl-forks"/></a>
</p>

<p align="center">
Base API-Rest with Laravel using <strong>Passport OAuth2 Authentication</strong>
</p>

## Environment setup

### First steps
Create a local environment file (`cp .env.example .env`). Set your credentials of the database
### Install dependencies
```
composer install
```
### Generate key
```
php artisan key:generate
```
### Migrate database
```
php artisan migrate --seed
```

### Create encryption keys
```
php artisan passport:install
```

### Create first client
```
php artisan passport:client
```
### Clear cache
```
php artisan optimize:clear
```

### List available routes
```
php artisan route:list
```
