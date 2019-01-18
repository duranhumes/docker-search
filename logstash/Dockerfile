# https://github.com/elastic/logstash-docker
FROM docker.elastic.co/logstash/logstash:6.5.4
USER root
COPY mysql-connector-java-5.1.44-bin.jar /opt/

RUN logstash-plugin install logstash-input-jdbc
RUN logstash-plugin install logstash-filter-aggregate
