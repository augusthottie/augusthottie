# Hey, I'm Jessica 👋

DevOps Engineer who builds infrastructure that doesn't break at 2am.

[![discord-badge]][main] [![gmail-badge]][gmail] [![twitter-badge]][twitter] [![linkedin-badge]][linkedin]

## What I Work With

```
Cloud:          AWS (VPC, ECS, EKS, RDS, ElastiCache, ALB, Lambda, API Gateway, DynamoDB, SQS, IAM, ECR)
IaC:            Terraform (modules, state management)
Containers:     Docker, ECS Fargate, Kubernetes, Helm, Kustomize, ArgoCD
CI/CD:          GitHub Actions, Jenkins, AWS CodePipeline, blue/green, GitOps
Languages:      Python, TypeScript, Bash
Observability:  Prometheus, Grafana, Loki, Promtail, PromQL, Alertmanager, CloudWatch
Other:          Linux, Git, Nginx
```

## Experience

**Lead DevOps Engineer** @ [Patara Labs](https://my.patara.app/) *(Aug 2024 – Present)*
> Run the Sui blockchain infrastructure — Jenkins CI/CD with zero-downtime deploys at 99.9% uptime, Prometheus/Grafana monitoring across Sui Network nodes, and Rust API container builds cut from 60 minutes to 15 through multi-stage builds and layer caching.

**DevOps Engineer** @ Notus Labs *(Jun 2023 – Jun 2024)*
> Built cloud infrastructure for Notus Network blockchain services. Architected the Explorer application behind AWS load balancers to 99.95% availability, and cut AWS spend 20% through right-sizing, reserved instances, and consolidation.

## Projects

**GitOps on EKS with Full Observability** · [`repo →`](https://github.com/augusthottie/gitops-eks)
Terraform-provisioned EKS cluster, Bun/Express API deployed via custom Helm chart with ArgoCD auto-sync and self-heal. 7 custom Prometheus metrics, a 9-panel Grafana dashboard, 9 alert rules, and Loki/Promtail log aggregation with metric-to-log correlation — click a spike, see the logs from that exact window.

**Serverless Event-Driven Data Pipeline** · [`repo →`](https://github.com/augusthottie/aws-serverless-event-pipeline)
Real-time pipeline across 4 Python Lambdas, API Gateway HTTP v2, DynamoDB with GSI, and SQS with a dead letter queue — 38 Terraform resources in 4 reusable modules. Async decoupling, atomic counters, conditional writes, partial batch failure handling. Runs at $3.60/month against $213 for the equivalent on EKS.

**3-Tier AWS Architecture & CI/CD** · [`repo →`](https://github.com/augusthottie/aws-3-tier-project)
Production-grade ECS Fargate + RDS PostgreSQL + ElastiCache Redis in a custom VPC, 6 Terraform modules and 37 resources, with an AWS-native pipeline doing blue/green deploys and automatic rollback.


## Hot Takes

- K8s is complicated for NOTHING and I will die on this hill
- If your rollback requires a human, it's not production-grade
- Most teams reaching for EKS need a Lambda and a queue

---

<sub>Portfolio: [augusthottie.com](https://www.augusthottie.com/) · You're not so average DevOps baddie</sub>

[main]: https://github.com/augusthottie
[linkedin]: https://www.linkedin.com/in/jessica-chioma-karchal/
[gmail]: mailto:jessicachiomachimex@gmail.com
[twitter]: https://twitter.com/augusthottie
[discord-badge]: https://img.shields.io/badge/augusthottie-black?logo=discord&style=for-the-badge
[gmail-badge]: https://img.shields.io/badge/Gmail-black?logo=gmail&style=for-the-badge
[twitter-badge]: https://img.shields.io/badge/augusthottie-black?logo=x&style=for-the-badge
[linkedin-badge]: https://img.shields.io/badge/Jessica%20Chioma%20Chimex-black?style=for-the-badge&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyMDAiIGhlaWdodD0iMjAwIiB2aWV3Qm94PSIwIDAgMjQgMjQiIGZpbGw9IiNmZmZmZmYiPjxwYXRoIGZpbGw9IiNmZmZmZmYiIGQ9Ik0xOSAzYTIgMiAwIDAgMSAyIDJ2MTRhMiAyIDAgMCAxLTIgMkg1YTIgMiAwIDAgMS0yLTJWNWEyIDIgMCAwIDEgMi0yaDE0bS0uNSAxNS41di01LjNhMy4yNiAzLjI2IDAgMCAwLTMuMjYtMy4yNmMtLjg1IDAtMS44NC41Mi0yLjMyIDEuM3YtMS4xMWgtMi43OXY4LjM3aDIuNzl2LTQuOTNjMC0uNzcuNjItMS40IDEuMzktMS40YTEuNCAxLjQgMCAwIDEgMS40IDEuNHY0LjkzaDIuNzlNNi44OCA4LjU2YTEuNjggMS42OCAwIDAgMCAxLjY4LTEuNjhjMC0uOTMtLjc1LTEuNjktMS42OC0xLjY5YTEuNjkgMS42OSAwIDAgMC0xLjY5IDEuNjljMCAuOTMuNzYgMS42OCAxLjY5IDEuNjhtMS4zOSA5Ljk0di04LjM3SDUuNXY4LjM3aDIuNzdaIi8+PC9zdmc+
