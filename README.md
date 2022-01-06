# ni-prometheus
Northinteractive Prometheus Deployment

```
docker run 
-d --name prometheus-container 
-e TZ=UTC 
-v /path/to/prometheus.yml:/etc/prometheus/prometheus.yml
-p 30090:9090 ubuntu/prometheus:2.28-21.10_beta
```