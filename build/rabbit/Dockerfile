ARG RABBITMQ_VERSION

FROM rabbitmq:${RABBITMQ_VERSION}

COPY rabbitmq_delayed_message_exchange-3.10.2.ez /plugins

WORKDIR /plugins

RUN rabbitmq-plugins enable rabbitmq_delayed_message_exchange