FROM grafana/grafana:13.0.11
USER root
RUN apk add --no-cache curl || (apt-get update && apt-get install -y --no-install-recommends curl && rm -rf /var/lib/apt/lists/*)
USER grafana
COPY provisioning /etc/grafana/provisioning
COPY dashboards /etc/grafana/dashboards
