# laravel-whois

<p align="center">Laravel 的 Whois 查询模块</p>

<p align="center">
<a href="https://packagist.org/packages/larva/laravel-whois"><img src="https://poser.pugx.org/larva/laravel-whois/v/stable.svg" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/larva/laravel-whois"><img src="https://poser.pugx.org/larva/laravel-whois/v/unstable.svg" alt="Latest Unstable Version"></a>
</p>

## 环境需求

- PHP >= 7.2.5

## Installation

```bash
composer require larva/laravel-whois -vv
```

```php
    $info=  \Larva\Whois\Whois::get('baidu.com');
    $info=  \Larva\Whois\Whois::getRaw('google.com');
```
