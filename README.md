# Laravel Quran

## install

```bash
composer require jhonoryza/laravel-quran
```

run migration

```bash
php artisan migrate
```

this will create 2 tables: qurans and quran_verses

publish config file

```bash
php artisan vendor:publish --tag=quran-config
```

kemenag source is using rest api method to get the data

tanzil.net source is using dump sql data that provided by tanzil to get the data

## sync data

sync quran

```bash
php artisan quran:sync
```

### Security

If you've found a bug regarding security please mail [jardik.oryza@gmail.com](mailto:jardik.oryza@gmail.com) instead of
using the issue tracker.

## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.
