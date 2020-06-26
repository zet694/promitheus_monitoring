FROM grafana/promtail:master-7212564

USER root

COPY conf/promtail-docker-config.yaml /etc/promtail/promtail-config.yaml

CMD ["-config.file=/etc/promtail/promtail-config.yaml"]