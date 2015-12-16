```php
<?php

$a->b = 123;

var_dump(isset($a));
var_dump($a);
var_dump($a->b);
```

```
PHP Warning:  Creating default object from empty value in /home/sekjun9878/Documents/Development/Projects/elphp/code3.php on line 3
bool(true)
object(stdClass)#1 (1) {
  ["b"]=>
  int(123)
}
int(123)
```
