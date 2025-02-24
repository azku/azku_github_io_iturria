---
title: Grafana
type: docs
---

BI tresna barruan denboran zehar adierazi behar diren grafikoentzako, Grafana software libre munduan aurkitu daitekeen aukera bat da.

Grafanaren gaitasunak erakusteko, datuak behar dira eta horretarako erabiliko dugu Prometheus node_explorerrekin. Bi hauek zerbitzari batean egongo dira instalatuta.

## Prometheus instalazioa
Prometheus Ansible birtartez instalatzeko [ondorengo esteka](https://github.com/azku/ansible_prometheus_node_exporter) erabili dezakegu.
## Grafana instalazioa
Grafana Ansible bitartez instalatzeko [ondorengo esteka](https://github.com/azku/ansible_grafana_metabase) erabili daiteke.
  
## Jarduera
Behin Grafana eta Prometheus sare berean instalatuta izanik node_exporterreko makinaren egoera azaleraraziko duten grafikoak egitea proposatzen da. Grafanaren gaitasun desberdinak probatzea da helburua.
