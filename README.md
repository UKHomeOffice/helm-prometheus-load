# Helm chart to deploy the Prometheus load application

[UKHomeOffice/docker-prometheus-load](https://github.com/UKHomeOffice/docker-prometheus-load) is a simple application publishing a pre-defined number of Prometheus metrics in order to load test agents scraping Prometheus metrics.

This Helm chart deploys this application and annotates the deployment to get those metrics scraped by Sysdig.

See [values.yaml](values.yaml) for a list of the supports chart parameters.