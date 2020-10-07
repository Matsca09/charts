# Automium Charts

Curated collection of Helm charts for Automium.

## Maintained

| Chart      | Description | Extra* |
| ----------- | ----------- | ----- |
| automium-cluster      | This chart creates and upgrades a Kubernetes cluster | no |
| automium-ingress   | This chart deploys the nginx ingress controller into a specific nodepool | no |
| automium-backup   | This chart provides components to backup a Kubernetes cluster | yes |
| automium-monitoring   | This chart provides components for monitoring a Kubernetes cluster | yes |

*Extra charts are not meant to be used directly by the user. Read the doc https://doc.automium.io/ for more info.

## Discontinued

* keepalived
* metrics-server
* nginx-ingress-controller

## License

MIT