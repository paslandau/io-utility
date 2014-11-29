#IOUtility
[![Build Status](https://travis-ci.org/paslandau/IOUtility.svg?branch=master)](https://travis-ci.org/paslandau/IOUtility)

IO library for file operations - mostly for convenience on commmon actions

##Description

##Requirements

- PHP >= 5.5
- goodby/csv >= 1.1

##Installation

The recommended way to install IOUtility is through [Composer](http://getcomposer.org/).

    curl -sS https://getcomposer.org/installer | php

Next, update your project's composer.json file to include IOUtility:

    {
        "repositories": [
            {
                "type": "git",
                "url": "https://github.com/paslandau/IOUtility.git"
            }
        ],
        "require": {
             "paslandau/IOUtility": "~0"
        }
    }

After installing, you need to require Composer's autoloader:
```php

require 'vendor/autoload.php';
```