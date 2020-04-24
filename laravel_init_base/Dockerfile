FROM virtualorz/php73_laravel_base

COPY ./init_base /var/project
RUN cd /var/project && composer install
WORKDIR /var/project
