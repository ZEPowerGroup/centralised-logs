FROM logstash:5.2.0-alpine

ADD conf /conf
RUN mkdir -p /tls/key /tls/cert
VOLUME /tls/key /tls/cert

CMD ["logstash", "-f", "/conf"]
