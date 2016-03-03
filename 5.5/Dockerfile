FROM php:5.5

RUN apt-get update -yqq \
    && apt-get install -yqq curl \
                            git \
    && docker-php-ext-install zip

RUN curl -sS https://getcomposer.org/installer | php && \
    mv composer.phar /usr/local/bin/composer