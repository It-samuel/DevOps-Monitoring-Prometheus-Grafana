# DevOps Monitoring Stack with Prometheus & Grafana

A complete monitoring solution for Azure App Services using Prometheus, Grafana, and Alertmanager with comprehensive alerting for uptime, performance, and infrastructure health.

## 🏗️ Architecture

- **Prometheus**: Metrics collection and alerting
- **Grafana**: Visualization and dashboards  
- **Alertmanager**: Alert routing and notifications
- **Blackbox Exporter**: Uptime and endpoint monitoring
- **Node Exporter**: Infrastructure metrics
- **Azure Monitor Exporter**: Azure-specific metrics

## 🚀 Features

- ✅ Website uptime monitoring
- ✅ SSL certificate expiry alerts
- ✅ Response time tracking
- ✅ Azure App Service metrics
- ✅ Email and Slack notifications
- ✅ Custom dashboards
- ✅ Infrastructure monitoring

## 📊 Monitored Metrics

### Application Metrics
- HTTP response times
- Status code distribution
- Error rates (4xx, 5xx)
- Request throughput
- SSL certificate validity

### Infrastructure Metrics
- CPU utilization
- Memory usage
- Disk space
- Network I/O

### Azure-Specific Metrics
- App Service instances
- Resource utilization
- Platform metrics

## 🛠️ Quick Start

1. Clone the repository
2. Configure your environment
3. Deploy the stack
4. Access dashboards

See [Setup Guide](docs/setup-guide.md) for detailed instructions.

## 📈 Dashboards

- **Application Overview**: High-level health metrics
- **Infrastructure**: System resource monitoring  
- **Azure App Service**: Platform-specific metrics
- **Alerts**: Current alert status

## 🔔 Alerting

Configured alerts for:
- Website downtime (< 1 minute)
- High response times (> 5 seconds)
- SSL expiry (< 30 days)
- Resource exhaustion (CPU > 80%, Memory > 85%)

## 🚀 Technologies Used

- Docker & Docker Compose
- Prometheus
- Grafana
- Azure Monitor
- YAML configuration
- Shell scripting

## 📝 Learning Objectives

This project demonstrates:
- Monitoring stack deployment
- Infrastructure as Code
- Alert configuration
- Dashboard creation
- DevOps best practices
