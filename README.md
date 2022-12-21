# News PHP
Google News fetcher

## Yukleme
```sh
composer require quiec/googlenewsphp
```

## Kullanim
```php
<?php
require __DIR__ . '/vendor/autoload.php';
$News = new Quiec\GoogleNews('tr', 'tr', 'BUSINESS', 100);
print_r($News->getNews());
```

## BOS
