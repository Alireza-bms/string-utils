# String Utils

---

Simple string utils for dealing easier with them

# Installation

Install using composer:

‌```
composer require Alireza-bms/string-utils
‌```

# Example

```php
<?php
require __DIR__ . '/vendor/autoload.php';

use \Alireza-bms\StringUtils\Str;

var_dump(Str::contains('abod', ['ab', 'x']));
```
