# php-style-guide
A guide for styling your php code

## Functions
```php
public function FunctionName($valueEmpty, $value = '', $value1 = true)
{
    # code...
    return $result;
}
```

### Statement blocks
```php
if (isValid || isSmexy) {
    # code...
} else {
    # code...
}
```

```php
switch ($variable) {
    case 'value':
        # code...
        break;
    case 'thing1':
    case 'thing2':
        # shared code...
        break;
    default:
        # code...
        break;
}
```

### Strings
```php
$string = "Part 1, " . $part2 . ", Part 3";
```
