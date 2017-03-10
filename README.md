### Name:
```php
/(name):\s?(\w+\s?)+/gi
```

### Email:
```php
/(email:)\s+(\w+\s?@\w+.\w+)/gi
```

### Indian Telephone regex
```php
/(tel|phone):\s?\d{2,5}-\d{6,8}/gi
```

### Indian Mobile regex
```php
/(mob|mobile):\s?(\+?\d{2}?-?\d{8,15})?(\d{8,15})?/gi
```

### Skype id regex:
```php
/(skype):\s?\w+/gi
```

### Indian Telephone Regex label + linefeed
```php
/(phone):\s?\\r?\\n?\s?\d{2,3}-\d{6,8}/gi
```

### Indian Mobile Regex label + linefeed
```php
/(mob|mobile):\s?\\r?\\n?(\+?\d{2}?-?\d{10})?(\d{10})?/gi
```

### Name Regex label + linefeed
```php
(name):\s?\\r?\\n?(\w+\s?)+
```

### Matches All `key:value` pairs including Phone number except Email
```php
([a-z]+):\s?((\w+,?\s)+)?(\+?\d.*)?
```

### Matches All `key:value` pairs except Email & Phone
```php
([a-z]+):\s?((\w+\s)+)
```

