FROM imply/imply

RUN sed 's/"druid-kafka-indexing-service",/"druid-avro-extensions", "druid-kafka-indexing-service",/' /opt/imply-2.7.6/conf-quickstart/druid/_common/common.runtime.properties > /tmp/sed && \
    mv /tmp/sed /opt/imply-2.7.6/conf-quickstart/druid/_common/common.runtime.properties
