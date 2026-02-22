# Laravel Test 2HOUNE

## Description

Ce projet contient :

### Niveau 1
API CRUD Products :
- GET /api/products
- POST /api/products
- PUT /api/products/{id}
- DELETE /api/products/{id}

### Niveau 2
Relation 1:N entre :
- Author (hasMany Books)
- Book (belongsTo Author)

## Installation

```bash
composer install
cp .env.example .env
php artisan key:generate
php artisan migrate
php artisan serve