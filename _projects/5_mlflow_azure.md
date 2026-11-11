---
layout: page
title: Self-Hosted MLflow on Azure
description: A self-hosted MLflow tracking platform for centralized experiment management.
img: assets/img/projects/mlflow_azure.png
importance: 5
category: engineering
---

A self-hosted **MLflow Tracking Server** deployed on an Azure Ubuntu VM to centralize experiment tracking for research projects.

<div class="row">
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid loading="eager" path="assets/img/projects/mlflow_azure.png" title="Self-hosted MLflow on Azure" class="img-fluid rounded z-depth-1" zoomable=true %}
  </div>
</div>
<div class="caption">
  Architecture of the self-hosted MLflow tracking platform.
</div>

- **Nginx** reverse proxy in front of the tracking server, with **Basic Auth** access control.
- **systemd** service management, so the server restarts automatically and survives reboots.
- Artifact tracking for models, metrics, and experiment outputs in one place.

**Stack:** MLflow, Azure, Ubuntu Linux, Nginx, systemd.
