# 🚀 BOCKER CLUSTER

Enterprise-grade Docker Swarm Cluster with:

- 🔐 Safe Docker Installation
- 🧠 HA Swarm Cluster
- 🌐 Traefik Loadbalancer
- 🔑 Authelia SSO
- 📊 Monitoring Stack
- 🛡️ CrowdSec Security

## Quick Start

```bash
ansible-playbook -i inventory/inventory.ini playbooks/01-docker-safe.yml
ansible-playbook -i inventory/inventory.ini playbooks/02-swarm-init.yml
ansible-playbook -i inventory/inventory.ini playbooks/03-traefik.yml
````
## 🧠 Architecture Overview

This diagram shows the core components of the BOCKER Cluster:

- Traefik as central routing layer
- Docker Swarm orchestration
- Authelia for authentication
- Monitoring via Prometheus & Grafana
- Security via CrowdSec & Fail2Ban

![Bocker Cluster](https://github.com/Steve72HH/bocker-cluster/blob/main/bocker-cluster.png)
![Bocker Cluster](https://github.com/Steve72HH/bocker-cluster/blob/main/Bocker-Cluster-System-Architektur.png)
