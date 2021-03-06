# laravel-doctrine-generators

[![Latest Version on Packagist][ico-version]][link-packagist]
[![Software License][ico-license]](LICENSE.md)
[![Build Status][ico-travis]][link-travis]
[![Total Downloads][ico-downloads]][link-downloads]

## Description

A set of generators for Laravel Doctrine.  Right now it only has a simple repository generator.  

## Install

Via Composer

``` bash
$ composer require isaackearl/laravel-doctrine-generators
```

## Usage

``` php
php artisan doctrine:make:repository User
// this will make a UserRepository (interface)
// and a DoctrineUserRepository (implementation)
// it will also generator a service provider if it is your first repository.
```

## Change log

Please see [CHANGELOG](CHANGELOG.md) for more information on what has changed recently.

## Contributing

Please see [CONTRIBUTING](CONTRIBUTING.md) and [CODE_OF_CONDUCT](CODE_OF_CONDUCT.md) for details.

## Credits

- [Isaac Earl][link-author]
- [All Contributors][link-contributors]

## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.

[ico-version]: https://img.shields.io/packagist/v/isaackearl/laravel-doctrine-generators.svg?style=flat-square
[ico-license]: https://img.shields.io/badge/license-MIT-brightgreen.svg?style=flat-square
[ico-travis]: https://img.shields.io/travis/isaackearl/laravel-doctrine-generators/master.svg?style=flat-square
[ico-scrutinizer]: https://img.shields.io/scrutinizer/coverage/g/isaackearl/laravel-doctrine-generators.svg?style=flat-square
[ico-code-quality]: https://img.shields.io/scrutinizer/g/isaackearl/laravel-doctrine-generators.svg?style=flat-square
[ico-downloads]: https://img.shields.io/packagist/dt/isaackearl/laravel-doctrine-generators.svg?style=flat-square

[link-packagist]: https://packagist.org/packages/isaackearl/laravel-doctrine-generators
[link-travis]: https://travis-ci.org/isaackearl/laravel-doctrine-generators
[link-scrutinizer]: https://scrutinizer-ci.com/g/isaackearl/laravel-doctrine-generators/code-structure
[link-code-quality]: https://scrutinizer-ci.com/g/isaackearl/laravel-doctrine-generators
[link-downloads]: https://packagist.org/packages/isaackearl/laravel-doctrine-generators
[link-author]: https://github.com/isaackearl
[link-contributors]: ../../contributors
