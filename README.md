
![License](https://img.shields.io/badge/License-MIT-green)
![Platform](https://img.shields.io/badge/Platform-Ubuntu-orange)
![DevOps](https://img.shields.io/badge/DevOps-Ready-blue)
![Automation](https://img.shields.io/badge/Automation-Enabled-blue)

# Nexoryx_VPN_Gateway

Production-ready VPN gateway and secure networking platform for Kubernetes and Linux infrastructure with WireGuard, OpenVPN, NGINX reverse proxy, firewall automation, monitoring, and secure remote access.

## Features

- WireGuard VPN server
- OpenVPN gateway
- NGINX reverse proxy
- Firewall automation
- Kubernetes-native deployment
- Secure remote access
- Persistent storage
- Monitoring integration
- Prometheus metrics
- Grafana dashboards
- Ingress support
- Production-ready manifests

## Stack

- Kubernetes
- WireGuard
- OpenVPN
- NGINX
- Prometheus
- Grafana
- Docker
- Linux Networking

## Deployment

```bash
kubectl apply -f kubernetes/
```

## Namespace

```bash
nexoryx-vpn
```

## Components

- WireGuard
- OpenVPN
- NGINX
- Prometheus
- Grafana
- Firewall Policies
- Ingress

## Notes

Replace VPN keys, certificates, passwords, and domains before production deployment.


## Project Roadmap

- [ ] Kubernetes Helm charts
- [ ] GitOps support
- [ ] CI/CD improvements
- [ ] Monitoring dashboards
- [ ] Multi-cloud support
- [ ] Security hardening

## GitHub Actions

This repository includes:
- Shell validation
- Markdown linting
- Terraform validation (where applicable)

## Example Deployments

See:
- examples/
- docs/

## Related Nexoryx Projects

This repository is part of the Nexoryx infrastructure ecosystem.
