# :package_description

[![Latest Version on Packagist](https://img.shields.io/packagist/v/:vendor_slug/:package_slug.svg?style=flat-square)](https://packagist.org/packages/:vendor_slug/:package_slug)
[![Tests](https://github.com/:vendor_slug/:package_slug/actions/workflows/run-tests.yml/badge.svg?branch=main)](https://github.com/:vendor_slug/:package_slug/actions/workflows/run-tests.yml)
[![Total Downloads](https://img.shields.io/packagist/dt/:vendor_slug/:package_slug.svg?style=flat-square)](https://packagist.org/packages/:vendor_slug/:package_slug)
<!--delete-->
---
This package can be used as to scaffold a framework agnostic package. Follow these steps to get started:

1. Press the "Use template" button at the top of this repo to create a new repo with the contents of this foo
2. Run "php ./configure.php" to run a script that will replace all placeholders throughout all the files
3. Have fun creating your package.
---
<!--/delete-->
This is where your description should go. Try and limit it to a paragraph or two. Consider adding a small example.

## Support us

We invest a lot of resources into creating [best in class open source packages](https://spatie.be/open-source). You can support us by [buying one of our paid products](https://spatie.be/open-source/support-us).

We highly appreciate you sending us a postcard from your hometown, mentioning which of our package(s) you are using. You'll find our address on [our contact page](https://spatie.be/about-us). We publish all received postcards on [our virtual postcard wall](https://spatie.be/open-source/postcards).

## Installation

You can install the package via composer:

```bash
composer require corals/foo
```

## Usage
new module from foo is created by the following command:
```php
php artisan make:module :modeule_name :model_name
```
###Example

---
php artisan make:module jobs job

- Jobs module that was created exist within the modules folder in corals folder
- It is ready to work on

## Testing

```bash
vendor/bin/phpunit vendor/corals/foo/tests 
```
## Credits

- [:author_name](https://github.com/:author_username)
