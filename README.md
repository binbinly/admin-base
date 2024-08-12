# admin-base

## install

```php

composer create-project laravel/laravel example-app

php artisan key:generate

composer require dcat/laravel-admin:"2.*" -vvv

>如果上一步出现报错，则更改 composer.json 的参数 minimum-stability 的值为 dev。

php artisan admin:publish

php artisan admin:install

'timezone' => 'Asia/Shanghai',
```

```nginx

location / {
    try_files $uri $uri/ /index.php?$query_string;
}

```

```php

composer require binbinly/dcat-admin-plus
```

