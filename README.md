# Weeyn Blog Post Module
Weeyn blog post module

![Packagist PHP Version](https://img.shields.io/packagist/dependency-v/weeynsoft/blog-post/php)
![Packagist Version](https://img.shields.io/packagist/v/weeynsoft/blog-post)
![Packagist Downloads](https://img.shields.io/packagist/dt/weeynsoft/blog-post?label=download)
![GitHub](https://img.shields.io/github/license/weeynsoft/blog-post)


This is the standalone blog post module of the [Weeyn](https://weeyn.com).

## Installation

(As Standalone Component)

1. `composer require weeynsoft/blog-post`
2. `php artisan vendor:publish --provider="Konekt\Concord\ConcordServiceProvider"`
3. Add `Weeyn\BlogPost\Providers\ModuleServiceProvider::class` to modules in `config/concord.php`
4. `php artisan migrate`

## Usage

See the [Weeyn Post Module Documentation](https://weeyn.com/docs/master/blog-post) for more details. 

## About Us

Weeyn development is led by the core team.