# Используйте образ PHP с веб-сервером Apache
FROM php:7.4-apache

# Копируйте файл index.php в каталог /var/www/html/
COPY index.php /var/www/html/

# Определите порт, на котором будет работать веб-сервер (8080)
EXPOSE 80

# Указание директории рабочей среды
WORKDIR /var/www/html
