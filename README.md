# PHP apache
php 7.2 apache for laravel, base on [PHP docker hub](https://hub.docker.com/_/php/)
## Supported tags
* 7.2.1, latest [(/7.2/apache/Dockerfile)](https://github.com/surasakv24/php-for-latavel/blob/master/7.2/apache/Dockerfile)
## Running
```
docker run -d -p 80:80 --name my-apache-php-app -v {app-path}:/var/www/html surasakv/php-for-latavel
```
## Other config
please see [PHP docker hub](https://hub.docker.com/_/php/)
