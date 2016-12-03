FROM rabbitmq

ADD entrypoint /entrypoint

VOLUME /var/lib/rabbitmq

ENTRYPOINT ["/bin/bash", "-c", "/entrypoint", "/docker-entrypoint.sh"]