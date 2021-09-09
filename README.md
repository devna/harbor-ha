# Harbor High Availability via Keepalived

The Ansible project helps to deploy Harbor with High Availability automatically. Different from [HA via Helm](https://goharbor.io/docs/2.3.0/install-config/harbor-ha-helm/) provided in official documents, this way doesn't depond on Kubernetes.

## Features
* Disable firewall/selinux
* Enable ipv4 forward
* Self-signed CA and host certificates generation
    * for Docker and Harbor
* Docker and docker-compose installation
* Harbor installation
* Keepalived installationss