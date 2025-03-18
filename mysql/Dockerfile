FROM mysql:5.7

ENV MYSQL_ALLOW_EMPTY_PASSWORD=yes \
    MYSQL_DATABASE=cities \
    MYSQL_USER=shipping \
    MYSQL_PASSWORD=RoboShop@1

COPY db/* /docker-entrypoint-initdb.d/