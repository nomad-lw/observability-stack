# Sambot's Observability Stack

## CAUTION

This project is still nascent and might not work out-of-the-box in every scenario. This is experimental, use at your own descretion

## What is this?

This ia a collection of tools and resources I am continusally experimenting with to help me understand how to build a robust observability stack for my projects.
It is meant to be a living project that I optomize towards what I consider the best practices.

## What is the stack?

--- #DRAFT from here ---

The stack is composed of the following components:

- Prometheus
- Grafana
- Loki
- Jaeger
- Thanos

### Prometheus

Prometheus is a time series database that allows you to store and query time series data.

### Grafana

Grafana is a dashboarding tool that allows you to visualize data from Prometheus.

### Loki

Loki is a log aggregation system that allows you to store and query logs.

### Jaeger

Jaeger is a distributed tracing system that allows you to trace requests across multiple services.

### Thanos

Thanos is a Prometheus-compatible monitoring system that allows you to store and query metrics.

## How do I use it?

I am currently using the following setup:

- Prometheus: https://prometheus.samast.dev
- Grafana: https://grafana.samast.dev
- Loki: https://loki.samast.dev
- Jaeger: https://jaeger.samast.dev
- Than


## System Requirements

The core stack requires a single machine with the following (minimum) requirements:

- CPU: 4 cores
- RAM: 8 GB
- Disk: 20 GB
- Static IP

## Deployment

The core stack requires a single machine at the moment so I use Docker Compose to deploy the stack.

To deploy the stack, run the following command:

```bash
docker-compose up -d
```

This will start all the services in the background.

To stop the stack, run the following command:

```bash
docker-compose down
```

This will stop all the services.

### Data persistence

### Backups

### Hardening







---

#### References
- https://www.elastic.co/guide/en/elasticsearch/reference/8.17/docker.html#docker-compose-file
