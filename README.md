Helm Chart Structure
A Helm chart typically has the following structure:

perl
Copy code
my-hello-world-chart/
├── Chart.yaml
├── values.yaml
├── templates/
│   ├── deployment.yaml
│   ├── service.yaml
│   └── ...
└── charts/
Chart.yaml: This file contains metadata about the chart like its name, version, and description.
values.yaml: Specifies default configuration values for the chart.
templates/: This directory contains template files that define Kubernetes resources like deployments and services.
charts/: Optional directory that may contain sub-charts upon which this chart depends.