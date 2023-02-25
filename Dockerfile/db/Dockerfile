FROM mysql:5.7.25
LABEL "Project"="Resume ranking"
LABEL "Author"="narendra"
ENV MYSQL_ROOT_PASSWORD="Encrypt password"
ENV MYSQL_DATABASE="accounts"
ADD db_backup.sql    docker-entrypoint-initdb.d/db_backup.sql
