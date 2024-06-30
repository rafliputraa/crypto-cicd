# Use the official Prometheus image from Docker Hub
FROM prom/prometheus:latest

# Copy the custom Prometheus configuration file to the container
COPY prometheus.yml /etc/prometheus/prometheus.yml

# Expose Prometheus port
EXPOSE 9090

# Command to run Prometheus
CMD ["--config.file=/etc/prometheus/prometheus.yml"]
