# Configuration for PHP Coding Standards Fixer

[![Version](https://img.shields.io/packagist/v/flexis/php-cs-fixer-config?label=stable)](https://packagist.org/packages/flexis/php-cs-fixer-config)
[![Build](https://img.shields.io/github/actions/workflow/status/flex-is/php-cs-fixer-config/ci.yaml?branch=main&logo=github)](https://github.com/flex-is/php-cs-fixer-config/actions/workflows/ci.yaml)
[![Coverage](https://app.codacy.com/project/badge/Coverage/246b2492dc404695b0deee6e6ecadc75)](https://www.codacy.com/gh/flex-is/php-cs-fixer-config/dashboard)
[![License: MIT](https://img.shields.io/badge/license-MIT-informational.svg)](https://opensource.org/licenses/MIT)

This repository was created for the purpose of introducing uniform coding standards for PHP code within [FLEX-IS](https://flexis.sk).

It is based on the ideas of [`refinery29/php-cs-fixer-config`](https://github.com/refinery29/php-cs-fixer-config).

## Installation

`$ composer require --dev flexis/php-cs-fixer-config`

## Usage

### Configuration

Create a configuration file [`.php-cs-fixer.dist.php`](/.php-cs-fixer.dist.php).

### Git

Add cache file created by PHP CS Fixer to `.gitignore`:

`.php-cs-fixer.cache`

## Fixing issues

To fix coding standards, simply run:

`$ php vendor/bin/php-cs-fixer fix`

> 💡 See the [official documentation](https://cs.symfony.com/doc/usage) for more examples.

## License

This package is licensed using the MIT License.
