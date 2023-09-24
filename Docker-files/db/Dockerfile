FROM mysql:8.0.33
LABEL "Project"="vprofile"
LABEL "Author"="Rishabh"

ENV MY_SQL_ROOT_PASSWORD="pass"
ENV MYSQL_DATABASE="accounts"

ADD db_backup.sql /docker-entrypoint-initdb.d/db_backup.sql