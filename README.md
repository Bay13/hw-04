# HW-04

## Подключение:

```json
"require": {
   "bay13/hw-04": "1.*"
}
```

```json
"repositories": [
   {
      "type": "vcs", 
      "url": "https://github.com/Bay13/hw-04.git"
   }
],
"require": {
   "bay13/hw-04": "1.*"
}
```

## Использование

```php
require __DIR__ . '/../vendor/autoload.php';

use Bay13\Hw04\ExampleClass;

$class = new ExampleClass();
echo $class->info();
```
