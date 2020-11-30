# SGMLUXURY **CODING ACADEMY**
[![forthebadge](https://forthebadge.com/images/badges/0-percent-optimized.svg)](https://forthebadge.com)
**Sharif, Gargani, Marco**.

## Laravel setup

### Install composer dependencies

```
cd laravel-app
composer install
```

### Database Migrations

After installing composer dependencies, add your database credentials in `.env` file and then run migrations.

```
php artisan migrate
```

Now, in the terminal run `artisan serve` command. It will run the application at `http://127.0.0.1:8000` URL, and that URL path used in the Vue.js app.

```
php artisan serve
```

If you are running the Laravel API on a different URL path, then you need to update the URL path in the `src/apis/Api.js` of the Vue.js app.

## Vue.js Project setup

```
cd vue-app
npm install
```

### Compiles and hot-reloads for development

```
npm run serve
```
