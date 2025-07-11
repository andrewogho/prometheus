# Prometheus
PromQL

Prometheus is an open-source monitoring and alerting system built originally at SoundCloud. It's now a part of the Cloud Native Computing Foundation (CNCF), just like Kubernetes.

It's designed for reliability, scalability, and performance monitoring, especially in cloud-native and microservice environments.


## Install Prometheus Node Exporter

![](img/a.install-pne.png)


## Start & Enable Node Exporter 

![](img/a.startnenable.png)

## Config Prometheus to Scrape Metrics from Node Exporter
![](img/b.nodeexp.png)

![](img/c.metrics.png)

![](img/c.mertrics1.png)



## Verify & Query Node Exporter metrics in Prometheus 

![](img/d.prom9090UI.png)

![](img/e.UI.png)

- Show the Prometheus server's own up status

![](img/f.qu.png)

- Show if Node Exporter is being scraped

![](img/g.qu.png)

- CPU usage over time
![](img/h.cpu.png)

- Available Disk Space on Root converted to GB
![](img/i.avaiabdisk.png)



- Show bytes received per second, over the last 1 minute
![](img/j.network%20bytes.png)
