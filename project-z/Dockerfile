FROM php:8.2-alpine

WORKDIR /app

COPY composer.json composer.lock

RUN composer install

COPY . .

EXPOSE 80

CMD ["apache2-foreground"]
