# Redirectoperators

Operators for performing URL redirect from within a template. The operators will send an HTTP header 301.

- `redirectabsolute`
- `redirectrelative`

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