## Deploy grafana and influxdb

Below we describe in details how to:

1. Install [Grafana](https://github.com/grafana/grafana)
2. Install [InfluxDb](https://github.com/influxdata/influxdb), which is used as datasourse with Grafana
3. Install [Telegraf](https://github.com/influxdata/telegraf) to collect server metrics.

*If you plan to use Grafana monitoring for your product feel free to copy this repository to your project and change variables as needed.*

### Requirements

Deployment to remote server is done using [Ansible](https://www.ansible.com/) - a simple automation tool. Deployment was tested on a brand new Digital Ocean Ubuntu 16.04 server. Some changes might required to run other linux distributives. Deployment steps includes:

1. Docker installation
2. Installation of [Grafana](https://github.com/grafana/grafana), [InfluxDb](https://github.com/influxdata/influxdb) and [Telegraf](https://github.com/influxdata/telegraf)
3. Running Grafana, InfluxDb, Telegraf inside Docker containers

### Prerequisites:

[Grafana](https://grafana.com/) is an open source, feature rich metrics dashboard and graph editor for Graphite, Elasticsearch, OpenTSDB, Prometheus and InfluxDB. It is lightweight, stupidly simple, free & [Docker](https://www.docker.com/) based. 

## Features

* 👌 **Setup** with a single command. 
* ️⚡️️ **Production deployment** automation behind [Nginx](https://nginx.org/en/) proxy.

## Getting Started

- [Deploy to production](SETUP.md).
