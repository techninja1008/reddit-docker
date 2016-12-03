FROM rabbitmq

ADD entrypoint /entrypoint

VOLUME /var/lib/rabbitmq

CMD ["/bin/bash", "-c", "/entrypoint", "rabbitmq-server"]