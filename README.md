# Kbot Configuration for OpenTelemetry Observability

This guide provides a sample configuration for setting up Kbot to send logs to [OpenTelemetry Collector] and metrics to [OpenTelemetry Collector] or [Prometheus].

## Prerequisites

- [Docker]
- [Docker Compose]

## How to Run

1. Export your telemetry token:

    ```bash
    export TELE_TOKEN=<TOKEN>
    ```

2. Start the services using Docker Compose:

    ```bash
    docker-compose up
    ```
