# Deprecated

This package is deprecated and can be replaced by using the `redirect` operator from composer package [Swark](https://github.com/Aplia/swark) instead.

ie. `{redirectrelative( '' )}` becomes `{redirect( '', 301 )}` and `{redirectabsolute( '' )}` becomes `{redirect( '', 301, 'abs' )}`.

# Redirectoperators

eZ publish legacy template operators for performing URL redirect from within a template. The operators will send an HTTP header 301.

- `redirectabsolute`
- `redirectrelative`

[![Latest Stable Version](https://img.shields.io/packagist/v/aplia/redirectoperators.svg?style=flat-square)](https://packagist.org/packages/aplia/redirectoperators)
[![Minimum PHP Version](https://img.shields.io/badge/php-%3E%3D%205.3-8892BF.svg?style=flat-square)](https://php.net/)


## Installation
Install with Composer:

```
composer require aplia/redirectoperators
```

## Usage
From within a template, write:
```
{redirectrelative( '' )}
```
for instance:
```
{redirectrelative( '/path/to/file.php' )}
```
or
```
{redirectabsolute( '' )}
```
for instance:
```
{redirectabsolute( '' )}
```
