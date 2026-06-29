# Internal Developer Platform Demo

A demonstration of an **Internal Developer Platform (IDP)** built with Kubernetes, Argo CD, Crossplane and (soon) Backstage.

## Goal

Demonstrate how Platform Engineering practices can provide a self-service developer experience through GitOps and Kubernetes.

```
Git
   │
   ▼
Argo CD
   │
   ▼
Crossplane
   │
   ▼
Platform API (XApp)
   │
   ▼
Namespace
ResourceQuota
LimitRange
```

## Current Features

- ✅ GitOps with Argo CD (App of Apps)
- ✅ Crossplane Platform API (`XApp`)
- ✅ Automatic namespace provisioning
- ✅ ResourceQuota provisioning
- ✅ LimitRange provisioning
- ✅ Self-healing infrastructure

## Roadmap

- ⏳ Backstage Portal
- ⏳ Monitoring (Prometheus / Grafana)
- ⏳ CI/CD
- ⏳ Golden Path