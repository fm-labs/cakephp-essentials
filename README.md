# CakePHP Core Essentials

Bundle of CakePHP essentials core libraries.

This package is a composer meta-package bundling
`cakephp`, `migrations`, `plugin-installer` and the `mobiledetect` libraries

Instead of adding and maintaining all core dependencies in each CakePHP project separately,
just drop in this package.

## Installation

```
 # In your CakePHP project directory

 composer config minimum-stability dev
 composer config prefer-stable 1
 composer require --dev fm-labs/cakephp-essentials dev-master
```

Note:
The first 2 composer commands `composer config minimum-stability dev` and
`config prefer-stable 1` are necessary because the
CakePHP Migration plugin dependency (cakephp/migrations) is not stable yet.

## Versioning

[TODO]

## Dev Tools

There is also a meta-package for various PHP/CakePHP developer tools:

[fm-labs/cakephp-devtools](https://github.com/fm-labs/devtools)
