FROM mysql:5.7.25
ENV MYSQL_ROOT_PASSWWORD="vprodbpass"
ENV MYSQL_DATABASE="accounts"
ADD db.backup.sql docker-entrypoint-initdb.d/db-backup.sql