FROM mysql:8.0.28

ADD backup.sql /docker-entrypoint-initdb.d

EXPOSE 3306

CMD ["mysqld"]