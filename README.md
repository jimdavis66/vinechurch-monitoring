# vinechurch-monitoring
Tools to monitor the Ubiquiti network and OBS live streams.

- Prometheus to collect metrics
- Prometheus exportes for Ubiquiti, macOS and OBS
- Grafana for visualisations

### Environment variables required
```
# Grafana
GF_SECURITY_ADMIN_USER=admin
GF_SECURITY_ADMIN_PASSWORD=password

# unifi-poller
UNIFI_USER=unpoller
UNIFI_PASS=password
UNIFI_URL=https://192.168.1.1:443

# obs-exporter
OBS_HOST=hostname
OBS_PORT=4455
OBS_PASSWORD=websocketpassword
OBS_LISTEN_PORT=5555
```