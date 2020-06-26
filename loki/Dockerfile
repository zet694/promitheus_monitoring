FROM grafana/loki:k23-aee064d

USER root

COPY conf/loki-local-config.yaml /etc/loki/loki-local-config.yaml

CMD ["-config.file=/etc/loki/loki-local-config.yaml"]