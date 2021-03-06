# laravel-intercom

[![Latest Version on Packagist](https://img.shields.io/packagist/v/liran-co/laravel-intercom.svg?style=flat-square)](https://packagist.org/packages/liran-co/laravel-intercom)
[![Total Downloads](https://img.shields.io/packagist/dt/liran-co/laravel-intercom.svg?style=flat-square)](https://packagist.org/packages/liran-co/laravel-intercom)

A simple wrapper for the [Intercom PHP library](https://github.com/intercom/intercom-php).

## Installation

You can install the package via composer:

```bash
composer require liran-co/laravel-intercom
```

## Usage

First, add the `INTERCOM_ACCESS_TOKEN` variable into your `.env` file.

Next, add the `Intercom` facade to the top of your file:

``` php
use Intercom;

// ...

Intercom::users()->getUsers([]);
```

That's it! Refer to [Intercom PHP](https://github.com/intercom/intercom-php) for usage information.

## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.