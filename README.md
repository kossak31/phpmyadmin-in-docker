sudo docker run --rm --name pma-socket -p 8080:80 -e PMA_SOCKET=/run/mysqld/mysqld.sock -v /run/mysqld/mysqld.sock:/run/mysqld/mysqld.sock phpmyadmin:latest
