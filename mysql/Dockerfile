FROM mysql/mysql-server:5.7

ENV DEBIAN_FRONTEND=noninteractive

RUN mysql -u root -c -e "CREATE USER 'laravel'@'172.21.0.%' IDENTIFIED BY '';"

RUN mysql -u root -c -e "GRANT ALL PRIVILEGES ON *.* TO 'laravel-4'@'172.21.0.%' IDENTIFIED BY '';"

RUN mysql -u root -c -e "FLUSH PRIVILEGES;"

CMD [ "mysqld" ]
