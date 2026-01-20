# Home Lab Prometheus + Grafana Configurations

This repository contains **sample configurations** for integrating **Prometheus** with **Grafana** in a home lab environment, for both **Windows** and **Linux** setups.

---

## Features

### Windows
- Prometheus + Grafana integration
- Preconfigured **alerts** for:
  - High CPU usage
  - High RAM usage
  - Low disk space

### Linux
- Docker Compose setup including:
  - Prometheus
  - Grafana
  - Node Exporter
  - Loki (for logs)
  - Promtail (log collection)
- Fully containerized for easy deployment

---

## Getting Started

### Prerequisites
- Docker & Docker Compose (for Linux)
- Windows environment with Prometheus, Node Exporter & Grafana installed

### Deployment
- **Windows:** Follow the configuration files to set up Prometheus and Grafana, and import alert rules.
- **Linux:** Run the Docker Compose stack:
  ```bash
  docker-compose up -d
