## Atul Kumar Khetan

**Senior Cloud Engineer (L5) at Uber** · Cloud, Colocation Data Centers & Site Reliability  
📍 Hyderabad, India · ✉️ [khetanatulz@gmail.com](mailto:khetanatulz@gmail.com) · 🔗 [linkedin.com/in/atul-khetan](https://linkedin.com/in/atul-khetan) · 🌐 [phantomhieve.github.io/profile](https://phantomhieve.github.io/profile/)

---

I design and operate large-scale infrastructure across public cloud (**AWS, GCP, Azure**) and physical **colocation data centers**. Over the past 7+ years, my work has centered on fleet observability, zero-trust infrastructure, GitOps delivery, and cloud FinOps—scaling systems from bare-metal racks and tethered device fleets to multi-region Kubernetes platforms running at `99.99%` availability.

Outside of work, I run a self-hosted Linux homelab (`phantomhive` server) and build quantitative personal finance tools, multi-account brokerage automation, and operational intelligence systems.

### Systems at Scale

```text
  [ Uber · 2026–Present ]     2,000+ hosts & 6,000+ tethered devices across 3 colocation data centers & 8 labs
                              100% fleet observability (Prometheus -> mTLS -> M3) · <4h 10GB cascade rollouts

  [ Sprinklr · 2025 ]         100+ CXM microservices on multi-region EKS & Kafka (KRaft) at 99.99% uptime
                              ArgoCD GitOps canary/blue-green delivery (-70% rollbacks, -45% MTTR, -25% AWS spend)

  [ MavQ / MTX · 2019–2025 ]  FedRAMP, NIST 800-53 & PCI DSS multi-cloud estates across AWS, GCP & Azure
                              ~$500K/yr (~40%) cloud cost reduction · KServe/Knative ML serving (-30% peak latency)
```

### Personal Engineering, Homelab & Finance Systems

When I'm not operating data center fleets at work, I enjoy self-hosting bare-metal Linux infrastructure at home—wired up with `systemd` services, `rsync`/SSH deployment pipelines, Prometheus `node_exporter` textfile collectors, and Grafana alerting—to run personal financial and operational workloads:

* **[finance](https://github.com/phantomhieve/finance) (Vault)** — Self-hosted personal finance & multi-asset portfolio platform tailored for the Indian financial ecosystem (Zerodha equities/MFs, US RSUs, EPF/NPS, real estate, and precious metals). Built on an ASGI dual-architecture (Django + native **Model Context Protocol `/mcp` server** with OAuth 2.0 PKCE), WebAuthn (Face ID/Touch ID) security, and a multi-stage **AI DAG engine** for FY tax harvesting (Sec 112A / 54EC) and portfolio stress-testing.
* **[kites-portfolio-automate](https://github.com/phantomhieve/kites-portfolio-automate)** — Unattended multi-account Zerodha Kite portfolio sync engine running on my home Ubuntu server. Uses headless Chromium (`Xvfb`) with automated TOTP injection and local OAuth callback interception to renew sessions hands-free, syncs cross-account holdings to Google Sheets with quota-aware state caching, and exports health telemetry to Prometheus.
* **[cashcenter](https://github.com/phantomhieve/cashcenter)** — Wholesale textile ledger and operational intelligence system built for merchant operations in North Bihar. Combines multi-year double-entry accounting with a 5-node AI DAG pipeline producing bilingual (**English / हिन्दी**) working-capital and turnaround briefs, deployed via automated GitHub Actions + SSH/systemd pipelines.
* **[family-tree](https://github.com/phantomhieve/family-tree)** — Interactive lineage visualization app built with Django, PostgreSQL, and vanilla JavaScript.

### Core Domains & Tooling

* **Cloud & Bare-Metal Estates:** AWS (EKS, EC2, VPC, Direct Connect, IAM), GCP (GKE, Cloud SQL, Cloud Armor), Azure, Colocation DCIM (NetBox), Rack/Subnet Auto-Discovery, KVM Virtualization, macOS & Linux Fleet Management
* **Orchestration & Delivery:** Kubernetes, Helm, ArgoCD (GitOps, Canary/Blue-Green), Apache Kafka (KRaft), KServe, Knative, Buildkite, GitHub Actions, GitLab CI
* **Infrastructure as Code:** Terraform, Ansible, Puppet, Bazel
* **Observability & SRE:** Prometheus, M3, Grafana, Loki, Tempo, Alertmanager, PagerDuty, PromQL, SLI/SLO Governance, Disaster Recovery
* **Security & Compliance:** Pomerium (Zero Trust), SSH Certificate Authorities, PKI/mTLS, HashiCorp Vault, Keycloak (OIDC/SSO), FedRAMP, PCI DSS, SOC 2, ISO 27001
* **Languages:** Python, Go, Bash, SQL

### Credentials

* **Certifications:** Google Cloud Certified — Professional Cloud Architect · Associate Cloud Engineer
* **Education:** B.Tech in Computer Science Engineering, Amity University, Jaipur (2015 – 2019)
