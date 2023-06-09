# PHP-библиотека OAuth-авторизации API Яндекса

Протокол OAuth 2.0 позволяет приложениям работать с сервисами Яндекса от имени пользователя. Доступ каждого приложения явно ограничивается правами, заданными при его регистрации. О базовых принципах OAuth, а также об особенностях протокола в Яндексе читайте раздел [Реализация OAuth в Яндексе](https://tech.yandex.ru/oauth/doc/dg/concepts/ya-oauth-intro-docpage/) документации. Библиотека написана на языке и содержит методы для OAuth-авторизации в Яндексе.  

* [Требования](#Требования)
* [Лицензия](#Лицензия)
* [Установка](#Установка)
* [Использование](#Использование)

## Требования

* PHP 5.6 или выше.
* Зарегистрированное приложение.


## Лицензия

Библиотека распространяется по [лицензии MIT](LICENSE.txt).

## Установка

Библиотека устанавливается с помощью пакетного менеджера [Composer](https://getcomposer.org).

1. Добавьте библиотеку в файл `composer.json` вашего проекта:

   ```json
   {
       "require": {
           "hamasakibrain/yandex-market-php-oauth": "*"
       }
   }
   ```

2. Включите автозагрузчик Composer в код проекта:

   ```php
   require __DIR__ . '/vendor/autoload.php';
   ```   


## Использование

[документация OAuth в Яндекс](https://tech.yandex.ru/oauth/doc/dg/concepts/about-docpage/).
