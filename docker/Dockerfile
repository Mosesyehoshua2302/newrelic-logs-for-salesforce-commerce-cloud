# Use the base image
FROM grafana/loki:2.9.1
COPY loki-config.yaml /mnt/config/loki-config.yaml
CMD ["-config.file=/mnt/config/loki-config.yaml"]
EXPOSE 3100
