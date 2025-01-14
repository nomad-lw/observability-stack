# fluentd/Dockerfile

FROM fluent/fluentd:v1.17-debian-1
USER root
RUN ["gem", "install", "fluent-plugin-elasticsearch", "--no-document"]
# RUN ["gem", "install", "fluent-plugin-", "--no-document"]
USER fluent
