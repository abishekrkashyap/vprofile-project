FROM mysql:8.0.33
LABEL "project"="Vprofile"
LABEL "Author"="Abishek"

ENV MY_SQL_ROOT_PASSWORD="vproddbpass"
ENV MY_SQL_DATABASES="accounts"

ADD db_backup.sql docker-entrypoint-initdb.d/db_backup.sql