# PHP Favorite Twist
	

## Ternary
```
$data['username'] = (isset($data['username']) ? $data['username'] : 'guest');
```

## PHP 7 - Coalesce
```
$username = $_SESSION['username'] ?? 'guest';
```

## PHP 7.4 Coalesce Assignment
```
$data['username'] ??= 'guest'
```

## Elvis Operator
```
foo = bar ?: baz;

roughly resolves to

foo = bar ? bar : baz;
```
