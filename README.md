# IDP GitOps Repository
Single source of truth for the IDP platform.
ArgoCD watches this repo and syncs changes to the cluster automatically.

## Structure
- apps/platform   → ArgoCD, Vault, Backstage
- apps/monitoring → Prometheus, Grafana, Loki
- apps/security   → Kyverno, SonarQube
- apps/workloads  → Developer applications
- infra/          → Terraform, namespace configs
