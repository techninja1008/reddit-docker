FROM rabbitmq

RUN rabbitmqctl add_vhost /
RUN rabbitmqctl add_user reddit reddit
RUN rabbitmqctl set_permissions -p / reddit ".*" ".*" ".*"

VOLUME /var/lib/rabbitmq