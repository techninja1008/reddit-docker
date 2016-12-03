FROM cassandra

ADD install.cql /install.cql
RUN cqlsh -h localhost -f /install.cql

VOLUME /var/lib/cassandra