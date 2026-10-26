FROM grafana/alloy:v1.21.2
USER root
RUN apt-get update && apt-get install -y --no-install-recommends curl && rm -rf /var/lib/apt/lists/*
COPY config.alloy /etc/alloy/config.alloy
