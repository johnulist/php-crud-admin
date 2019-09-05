# PHP-CRUD-ADMIN

Single file PHP script that adds an database admin interface to a [PHP-CRUD-API](https://github.com/mevdschee/php-crud-api) project

## Requirements

  - PHP 7.0 or higher with Curl enabled
  - An URL of PHP-CRUD-API v2

## Installation

This is a single file application! Upload "`admin.php`" somewhere and enjoy!

For local development you may run PHP's built-in web server:

    php -S localhost:8080

Test the script by opening the following URL:

    http://localhost:8080/admin.php/

Don't forget to modify the configuration at the bottom of the file.

## Compilation

You can compile all files into a single "`admin.php`" file using:

    php build.php

You can access the non-compiled code at the URL:

    http://localhost:8080/src/

The non-compiled code resides in the "`src`" and "`vendor`" directories. The "`vendor`" directory contains the dependencies.