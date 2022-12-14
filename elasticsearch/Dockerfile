ARG ELK_VERSION

FROM elasticsearch:${ELK_VERSION}

COPY --chown=elasticsearch:root config/elasticsearch.yml /usr/share/elasticsearch/config/elasticsearch.yml
RUN ls -alh /usr/share/elasticsearch/config/