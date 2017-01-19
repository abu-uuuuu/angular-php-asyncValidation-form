# angular-php-asyncValidation-form
PHP rest api server + Angular asyncronous validation form (with Bootstrap)

Инструкция по установке

1. Скачайте и распакуйте архив leko-registration-form.7z:

    Структура директорий:

    - db - БД

    - leko-registration-form - исходники проекта (frontend и backend - в директории rest-api)

    - ТЗ - техзадание

2. Создайте БД из скрипта leko.sql 

3. Создайте пользователя leko с паролем leko (или задайте параметры соединения с БД в файле config.php)

4. Создайте виртуальный хост. Пример записи из httpd-vhosts.conf

<VirtualHost *:80\>
    DocumentRoot "D:\www\vhosts\leko-registration-form"
    ServerName leko-registration-form
</VirtualHost\>

Возможно что будет работать и без виртуального хоста.

5. Должен быть подключен apache модуль rewrite_module

LoadModule rewrite_module modules/mod_rewrite.so

6. в php.ini разрешите расширения: pdo
extension=php_pdo_mysql.dll

http://leko-registration-form/
