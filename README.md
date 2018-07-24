### Usage

```sh
make  run                 # builds grafana and prometheus 
                          # images and initializes all three containers 
                          # that forms the infra (grafana, prometheus and 
                          # node_exporter).  

make  update-dashboards   # updates the list of json files that represent
                          # the dashboards configured in Grafana.

```

### More

See:

- [How to Collect Docker Daemon Metrics](https://ops.tips/gists/how-to-collect-docker-daemon-metrics/).
- [Initializing Grafana with preconfigured dashboards](https://ops.tips/blog/initialize-grafana-with-preconfigured-dashboards/).
