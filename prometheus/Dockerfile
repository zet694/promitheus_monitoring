FROM prom/prometheus:v2.19.1
# https://hub.docker.com/r/prom/prometheus/tags/

COPY conf /etc/prometheus/

ENTRYPOINT ["sh", "/etc/prometheus/docker-entrypoint.sh" ]
CMD        [ "--config.file=/etc/prometheus/prometheus.yml", \
             "--storage.tsdb.path=/prometheus" ]
