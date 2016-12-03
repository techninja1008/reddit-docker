FROM postgres

ADD install.sql /install.sql
USER postgres
RUN createdb -E utf8 reddit
RUN psql -f /install.sql reddit
USER root

VOLUME /var/lib/postgresql/data