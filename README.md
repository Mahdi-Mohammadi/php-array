#PHP Array

PHP class to Operation an Array

#About v0.2

PHP have useful arrays function(like:array_map, array_diff,...) but I think those functions can be better and powerful so I write this class.
My approach is like CakePHP Hash Utility Class.

#Requirements

Php Array Requires **PHP >= 5.4**  

#Installation

##Using Composer

You can install this package using [composer](https://getcomposer.org). Add this package to your `composer.json`:  

```
"require": {
	"mahdi-mohammadi/php-array": "dev-master"
}
```

or if you prefer command line, change directory to project root and:

```
php composer.phar require "mahdi-mohammadi/php-array":"dev-master"
```

##Manual Installation

Get a copy of package source code. You can do this in two ways:

1. Download ZIP version of the source code and unzip it in desired location  
2. Run `git clone https://github.com/mahdi-mohammadi/php-array.git` to clone this repository  

After getting a copy of source code, it is enough to include `phpArray.class.php` where you need to use it.

```php
require_once 'path/to/source/phpArray.class.php';
```

#Examples

Please see [examples.php](examples.php) and [example-static.php](examples-static.php) for working examples.


##License
Hash Class was created by [CakePHP](http://cakephp.org) and released under the [MIT License](http://opensource.org/licenses/mit-license.php) so Php Array released under the [MIT License](http://opensource.org/licenses/mit-license.php) too.

Copyright (C) 2015 Mahdi Mohammadi


#Resources
- [CakePhp Hash](http://book.cakephp.org/3.0/en/core-libraries/hash.html)  
