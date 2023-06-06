# Prometheus
Projeto de estudo com uso de Prometheus e Grafana, utilizando a aplicação Node.JS


### Node

Comando para subir a aplicação Node, entre na pasta app e execute o comando node ./index.js


### Prometheus

Comando para subir o prometheus

docker run --name prometheus -d -p 9090:9090 -v /caminhofisico_ondefoiefetuadodownload/prometheus/prometheus/prometheus.yml:/etc/prometheus/prometheus.yml prom/prometheus


### Grafana

Comando para subir o Grafana

docker run -d --name=grafana -p 3000:3000 grafana/grafana