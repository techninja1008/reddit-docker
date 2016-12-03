FROM cassandra

ADD install.cql /install.cql
RUN cassandra-cli -h localhost -f /install.cql

VOLUME /var/lib/cassandra