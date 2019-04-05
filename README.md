# Laravel Make User
## v5.0.0

[![Build Status](https://travis-ci.org/michaeldyrynda/laravel-make-user.svg?branch=master)](https://travis-ci.org/michaeldyrynda/laravel-make-user)
[![Scrutinizer Code Quality](https://scrutinizer-ci.com/g/michaeldyrynda/laravel-make-user/badges/quality-score.png?b=master)](https://scrutinizer-ci.com/g/michaeldyrynda/laravel-make-user/?branch=master)
[![Code Coverage](https://scrutinizer-ci.com/g/michaeldyrynda/laravel-make-user/badges/coverage.png?b=master)](https://scrutinizer-ci.com/g/michaeldyrynda/laravel-make-user/?branch=master)
[![Latest Stable Version](https://poser.pugx.org/dyrynda/laravel-make-user/v/stable)](https://packagist.org/packages/dyrynda/laravel-make-user)
[![Total Downloads](https://poser.pugx.org/dyrynda/laravel-make-user/downloads)](https://packagist.org/packages/dyrynda/laravel-make-user)
[![License](https://poser.pugx.org/dyrynda/laravel-make-user/license)](https://packagist.org/packages/dyrynda/laravel-make-user)
[![Dependency Status](https://www.versioneye.com/php/dyrynda:laravel-make-user/dev-master/badge?style=flat-square)](https://www.versioneye.com/php/dyrynda:laravel-make-user/dev-master)

## Introduction

Out of the box, Laravel makes it really simple to scaffold out with its [authentication quickstart](https://laravel.com/docs/5.8/authentication#authentication-quickstart). Whilst this makes it really easy to register and authenticate users, for many of the applications I find myself building, we usually remove the ability for visitors to register themselves.

I still need a way to get users into those applications, however, and whilst they're in early development this usually involves firing up Laravel Tinker. This can be a tedious process, and one that I repeat many times over.

This package aims to solve the repetition problem by providing a convenient `make:user` Artisan command.

### Version compatibility

Laravel | Package
:-------|:--------
5.4.*   | 1.0.*
5.5.*   | 2.0.*
5.6.*   | 3.0.*
5.7.*   | 4.0.*
5.8.*   | 5.0.*

## Code Samples

This package exposes a `make:user` command, which is accessed via the Artisan command line utility. The package will use the model defined in your `auth.providers.users.model` configuration value.

```
php artisan make:user
```

This package runs on the assumption that you are using Laravel's default `users` table structure. You can specify additional fields when prompted.

## Installation

This package is installed via [Composer](https://getcomposer.org/). To install, run the following command.

```bash
composer require "dyrynda/laravel-make-user:~4.0"
```

## Support

If you are having general issues with this package, feel free to contact me on [Twitter](https://twitter.com/michaeldyrynda).

If you believe you have found an issue, please report it using the [GitHub issue tracker](https://github.com/michaeldyrynda/laravel-make-user/issues), or better yet, fork the repository and submit a pull request.

If you're using this package, I'd love to hear your thoughts. Thanks!
