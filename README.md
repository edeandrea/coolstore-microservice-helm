---
page_type: sample
languages:
- yaml
products:
- MAD
description: "Helm charts for MAD Coolstore"
urlFragment: mad-helm-charts-coolstore
---

# MAD Coolstore Samples - Helm Charts

## Configuration

Add the MAD Coolstore chart repository.

```
helm repo add mad-coolstore-microservice https://rh-mad-workshop.github.io/coolstore-microservice-helm
```

## Installation

Install the chart:

```shell
helm install coolstore mad-coolstore-microservice/coolstore-microservice -n <namespace> --wait
```

## Chart source

All chart source material including chart readme files are found under the [chart-source directory](/chart-source/).