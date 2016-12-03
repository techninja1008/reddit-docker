FROM cassandra

ADD install.cql /install.cql

VOLUME /var/lib/cassandra
ADD entrypoint /entrypoint

CMD ["/bin/bash", "-c", "/entrypoint", "cassandra", "-f"]