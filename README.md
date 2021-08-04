UPnL Kubernetes
========

- [`infra/`]: "infra" is YAMLs which should be deployed ahead of "service"
  YAMLs. It includes CertManager, Storage Class, etc.
- [`service/`]: "service" is actual YAMLs for UPnL services.

[`infra/`]: infra/
[`service/`]: service/

See [upnl/infra](https://github.com/upnl/infra) for Terraform codes of UPnL infrastructure.

You should replace `*.secret.yml.example` with your own secrets to use this YAMLs properly. And you should setup docker image registries (ex: `/etc/rancher/k3s/registries.yaml`) to use GHCR docker images properly.
