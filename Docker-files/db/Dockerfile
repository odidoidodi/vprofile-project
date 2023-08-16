FROM mysql:8.0.33
LABEL "Project"="Idodi"
ENV MYSQL_ROOT_PASSWORD="test"
ENV MYSQL_DATABASE="accounts"
ADD db_backup.sql docker-entrypoint-initdb.d/db_backup.sql

