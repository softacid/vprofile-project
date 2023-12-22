FROM mysql:8.0.33
LABEL "Project"="Vprofile"
LABEL "Author"="Teo"

ENV MSQL_ROOT_PASSWORD="admin1234"
ENV MSQL_DATABASE="accounts"

ADD db_backup.sql docker-entrypoint-initdb.d/db_backup.sql

