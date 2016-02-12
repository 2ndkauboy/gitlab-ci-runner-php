FROM php:7.0

RUN apt-get update -yqq \
    && apt-get install -yqq curl \
                            git

RUN curl -sS https://getcomposer.org/installer | php && \
    mv composer.phar /usr/local/bin/composer