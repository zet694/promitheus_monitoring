FROM prom/node-exporter:v1.0.1
ENV NODE_ID=none
COPY conf /etc/node-exporter/
ENTRYPOINT  ["sh", "/etc/node-exporter/docker-entrypoint.sh"]
CMD ["/bin/node_exporter"]
