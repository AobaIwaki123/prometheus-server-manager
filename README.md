# Prometheus Server Manager

## About

Provide Simple Server Management Tools with Promethus

## Getting Started

```sh
$ cp alertmanager/default-config.yml alertmanager/config.yml
$ cp prometheus/default-alert.rules.yml prometheus/alert.rules.yml
$ sudo docker volume create metrics_data
$ sudo docker compose up -d
```

## Support

- Alertmanager
- Exporter
  - Node Exporter

## Usage

### Node Exporter

### Alertmanager