FROM cassandra

ADD install.cql /install.cql

VOLUME /var/lib/cassandra
ADD entrypoint /entrypoint

ENTRYPOINT ["/bin/bash", "-c", "/entrypoint", "/docker-entrypoint.sh"]