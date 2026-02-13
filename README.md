# docker-LGTM

Originally forked from [docker-monitoring-stack-gpnc](https://github.com/ruanbekker/docker-monitoring-stack-gpnc)

_Kept up-to date with [Renovatebot](https://github.com/renovatebot/renovate)_
  * See [Dependency Dashboard](https://github.com/hollanbm/docker-LGTM/issues/3)

## Before getting started

`docker create network MONITORING`

`NPM` is the name of my reverse proxy network. Update to match yours

## Features

* [Grafana](https://github.com/grafana/grafana)
* [Prometheus](https://github.com/prometheus/prometheus)
* [AlertManager](https://github.com/prometheus/alertmanager)
* [Grafana Loki](https://github.com/grafana/loki)
* [Grafana Alloy](https://github.com/grafana/alloy)

## Prometheus Exporters

* [node-exporter](https://github.com/prometheus/node_exporter) via Alloy built-in [prometheus.exporter.unix](https://grafana.com/docs/alloy/latest/reference/components/prometheus/prometheus.exporter.unix/)
* [cadvisor](https://github.com/google/cadvisor) via Alloy built-in [prometheus.exporter.cadvisor](https://grafana.com/docs/alloy/latest/reference/components/prometheus/prometheus.exporter.cadvisor/)
* [exportarr](https://github.com/onedr0p/exportarr)
* [tdarr exporter](https://github.com/homeylab/tdarr-exporter)
* [unpoller](https://github.com/unpoller/unpoller)
* [smartctl-exporter](https://github.com/prometheus-community/smartctl_exporter)
