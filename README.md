# monitoring-project# Website Monitoring & Alerting

## Project Overview

A DevOps monitoring project that monitors website availability using **Prometheus, Blackbox Exporter, Grafana, and Alertmanager**.

## Architecture

```text
Website
   ↓
Blackbox Exporter
   ↓
Prometheus
   ↓
Grafana
   ↓
Alertmanager → Email Alert
```

## Technologies Used

* Linux
* AWS EC2
* Prometheus
* Blackbox Exporter
* Grafana
* Alertmanager
* Git & GitHub

## Monitoring

The project monitors:

* Website availability
* HTTP/HTTPS status
* Response time
* DNS lookup time
* SSL/TLS certificate information

## Alerting

Alerts are configured in Prometheus and routed through Alertmanager.

Example:

```text
Website Down
     ↓
Prometheus Alert
     ↓
Alertmanager
     ↓
Email Notification
```

## Security

**No passwords, API keys, SMTP credentials, or other secrets are stored in this repository.**

## Project Structure

```text
monitoring-project/
├── prometheus/
├── blackbox/
├── alertmanager/
├── grafana/
└── README.md
```

## Author

**Mohammed Zaka Ulla**
