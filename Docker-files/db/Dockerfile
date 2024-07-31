FROM mysql:latest
LABEL "Project"="vprofile"
LABEL "Author"="vivek"

ENV MYSQL_ROOT_PASSWORD="vprodbpass"
ENV MYSQL_DATABASE="accounts"

ADD db_backup.sql docker-entrypoint-initdb.d/db_backup.sql