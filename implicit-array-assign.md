```php
<?php

$a['hello'] = 123;

var_dump(isset($a));
var_dump($a);
var_dump($a['hello']);
```

```
bool(true)
array(1) {
  ["hello"]=>
  int(123)
}
int(123)
```
