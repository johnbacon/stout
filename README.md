<p align="center"><img src="https://github.com/johnbacon/stout/raw/HEAD/art/logo.svg" width="100" alt="Logo Stout"></p>

<p align="center">
    <a href="https://github.com/johnbacon/stout/actions/tests.yml"><img src="https://github.com/johnbacon/stout/workflows/tests/badge.svg" alt="Build Status"></a>
    <a href="https://packagist.org/packages/johnbacon/stout"><img src="https://img.shields.io/packagist/dt/johnbacon/stout" alt="Total Downloads"></a>
    <a href="https://packagist.org/packages/johnbacon/stout"><img src="https://img.shields.io/packagist/v/johnbacon/stout" alt="Latest Stable Version"></a>
    <a href="https://packagist.org/packages/johnbacon/stout"><img src="https://img.shields.io/packagist/l/johnbacon/stout" alt="License"></a>
</p>

<a name="introduction"></a>

## Introduction

**Stout** is a fork of [**Laravel Pint**](https://github.com/laravel/pint), which is itself built on top of **[PHP-CS-Fixer](https://github.com/FriendsOfPHP/PHP-CS-Fixer)**.

The only difference between **Pint** and **Stout** is the ability to specify which indentation styles and line-endings you prefer.

## Official Documentation

### Installation

```bash
composer require johnbacon/stout --dev
```

### Usage

Use the same commands as Pint:

```bash
php ./vendor/bin/stout
```

or

```bash
php ./vendor/bin/stout --dirty
```

To change the indentation, add the indent option to `stout.json`:

```json
{
  "indent": "\t"
}
```

Default for intentation is **4 spaces.**

To change the line ending option:

```json
{
  "lineEnding": "\r\n"
}
```

Default line ending is a single **newline.**

<a name="security-vulnerabilities"></a>

## Security Vulnerabilities

Please review [our security policy](https://github.com/johnbacon/stout/security/policy) on how to report security vulnerabilities.

<a name="license"></a>

## License

Stout is open-sourced software licensed under the [MIT license](LICENSE.md).
