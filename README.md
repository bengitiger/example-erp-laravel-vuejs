# ERP Example

An example of an ERP system developed with [Laravel][laravel-link], build with the preset bootstrap/vuejs.  Other presets can be found in:

* [example-erp-laravel-bootstrap][example-erp-laravel-bootstrap-link]
* [example-erp-laravel-react][example-erp-laravel-react-link]

## How to use

```shell
git clone https://github.com/afgloeden/example-erp-laravel-vuejs.git

cp -v .env.example .env
# Update .env to your settings

composer install
composer dump-autoload -o

php artisan key:generate

php artisan migrate
php artisan db:seed

npm install
npm run prod

php artisan route:cache
php artisan config:cache
```

## Tests

```shell
npm run tests
```

[laravel-link]: https://laravel.com/
[example-erp-laravel-bootstrap-link]: https://github.com/afgloeden/example-erp-laravel-bootstrap
[example-erp-laravel-react-link]: https://github.com/afgloeden/example-erp-laravel-react