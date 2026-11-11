---
layout: page
title: Self-hosted MLflow on Azure
description: A self-hosted MLflow tracking platform for centralized experiment management.
importance: 5
category: engineering
---

A self-hosted **MLflow Tracking Server** deployed on an Azure Ubuntu VM to centralize experiment tracking for research projects.

- **Nginx** reverse proxy in front of the tracking server, with **Basic Auth** access control.
- **systemd** service management, so the server restarts automatically and survives reboots.
- Artifact tracking for models, metrics, and experiment outputs in one place.

**Stack:** MLflow, Azure, Ubuntu Linux, Nginx, systemd.
