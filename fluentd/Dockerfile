# fluentd/Dockerfile

FROM fluent/fluentd:v1.12.0-debian-1.0
USER root

## Elastic Search
RUN ["gem", "install", "fluent-plugin-elasticsearch", "--no-document"]
USER fluent