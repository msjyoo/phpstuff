```php
<?php

var_dump(isset($b));
var_dump($b);

$a = &$b;

var_dump(isset($b));

var_dump($a);
var_dump($b);

$b = NULL;

var_dump(isset($b));
```

```
bool(false)
PHP Notice:  Undefined variable: b in code3.php on line 4
NULL
bool(false)
NULL
NULL
bool(false)
```
