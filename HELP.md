# Prometheous

1. Get prometheous docker image
   2. docker pull prom/prometheus
2. Start propetheous server
   3. fow linux - docker run -p 9090:9090 -v F:\Grafana\grafana-lrn\grafana-lrn\src\main\resources\prometheus.yml prom\prometheus
   4. for windows - docker run -p 9090:9090 -v F:/Grafana/grafana-lrn/grafana-lrn/src/main/resources/prometheus.yml prom/prometheus


# Grafana
1. Get Grafana docker image 
   2. docker pull grafana/grafana
2. Start grafana server
   3. docker run -d --name=grafana -p 3000:3000  grafana/grafana
