FROM fluent/fluentd:v1.12.0-1.0
USER root
RUN fluent-gem install fluent-plugin-netflow
RUN fluent-gem install fluent-plugin-elasticsearch
RUN fluent-gem install fluent-plugin-dict-map
COPY config /fluentd/etc
COPY dictionaries /fluentd/etc
USER fluent
