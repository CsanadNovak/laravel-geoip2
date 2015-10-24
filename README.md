# GeoIP2 for Laravel

## Install

Via Composer

``` bash
$ composer require csanadnovak/laravel-geoip2
```

``` php
'providers' => array(
    'CsanadNovak\LaravelGeoIP2\GeoIP2ServiceProvider:class',
)
```

``` php
'aliases' => array(
    'GeoIP2' => 'CsanadNovak\LaravelGeoIP2\GeoIP2Facade',
)
```

``` php
$ php artisan config:publish csanadnovak/laravel-geoip2
```
