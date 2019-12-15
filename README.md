UPnL Kubernetes
========

- [`infra/`]: "infra" is YAMLs which should be deployed ahead of "service"
  YAMLs. It includes Cloud Controller Manager, Storage Class, etc.
- [`service/`]: "service" is actual YAMLs for UPnL services.
- [`test/`]: "test" is YAMLs that are not actually deployed to the UPnL
  Kubernetes. It contains YAML snippets for testing and debugging.

[`infra/`]: infra/
[`service/`]: service/
[`test/`]: test/

See [upnl/infra](https://github.com/upnl/infra) for Terraform codes of UPnL infrastructure.
