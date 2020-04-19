# CakePHP Essentails

Bundle of CakePHP essentials core library.

This package is a composer meta-package bundling
`cakephp`, `migrations`, `plugin-installer` and the `mobiledetect` libraries

Instead of adding and maintaining all core dependencies in each CakePHP project,
just use this package.

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
CakePHP Migration plugin dependency (cakephp/migration) is not stable yet.

