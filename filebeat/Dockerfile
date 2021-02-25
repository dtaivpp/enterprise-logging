# https://www.docker.elastic.co/

FROM docker.elastic.co/beats/filebeat-oss:7.11.0
COPY config/filebeat.yml /usr/share/filebeat/filebeat.yml
USER root
RUN chown root:filebeat /usr/share/filebeat/filebeat.yml
USER filebeat