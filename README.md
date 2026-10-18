<div align="center">

# Atul Kumar Khetan
### Senior Cloud Engineer @ Uber | Cloud & Data Center Infrastructure | Kubernetes • Terraform • Observability

[![LinkedIn](https://img.shields.io/badge/LinkedIn-atul--khetan-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/atul-khetan)
[![Email](https://img.shields.io/badge/Email-khetanatulz%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:khetanatulz@gmail.com)
[![Portfolio](https://img.shields.io/badge/Portfolio-phantomhieve.github.io-181717?style=for-the-badge&logo=github&logoColor=white)](https://phantomhieve.github.io/profile/)
[![Location](https://img.shields.io/badge/Location-Hyderabad%2C%20India-2ea44f?style=for-the-badge&logo=googlemaps&logoColor=white)](#)

</div>

---

### ⚡ About Me

Senior Cloud Engineer with **7+ years** designing and operating large-scale infrastructure across public cloud and colocation data centers:
- 🔭 **Currently at Uber (L5):** Owning observability, automation, and capacity for a **2,000+ host, 6,000+ device fleet** across **3 colocation data centers** & 8 physical device labs.
- ☸️ **Cloud & Platform Engineering:** Previously led DevOps for **100+ microservices** on multi-region **EKS** & **Kafka (KRaft)** at **99.99% uptime** using GitOps (**ArgoCD**) with canary & blue-green rollouts.
- 💰 **FinOps & Reliability:** Cut cloud spend **~40% (~$500K annually)** through Terraform-driven autoscaling, right-sizing, and spot strategies; owned SLO-based alerting and on-call across AWS, GCP, and bare-metal estates.
- 🔒 **Security & Compliance:** Delivered **FedRAMP, NIST 800-53, PCI DSS, SOC 2, and ISO 27001** compliant platforms with Zero Trust (**Pomerium**), SSH Certificate Authorities, **PKI/mTLS**, **HashiCorp Vault**, and **OIDC/IRSA**.

---

### 🛠️ Technical Stack

| Category | Technologies & Tools |
| :--- | :--- |
| **Cloud Platforms** | ![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white) (EKS, EC2, S3, IAM, VPC, Direct Connect, Secrets Manager) • ![GCP](https://img.shields.io/badge/GCP-4285F4?style=flat-square&logo=googlecloud&logoColor=white) (GKE, Cloud SQL, Memorystore, Cloud Armor, GCS) • ![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white) |
| **Containers & Orchestration** | ![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![Helm](https://img.shields.io/badge/Helm-0F1689?style=flat-square&logo=helm&logoColor=white) ![ArgoCD](https://img.shields.io/badge/ArgoCD-EF7B4D?style=flat-square&logo=argo&logoColor=white) GitOps • KServe • Knative • KVM • ![Apache Kafka](https://img.shields.io/badge/Kafka_(KRaft)-231F20?style=flat-square&logo=apachekafka&logoColor=white) |
| **Infrastructure as Code (IaC)** | ![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=flat-square&logo=terraform&logoColor=white) ![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=flat-square&logo=ansible&logoColor=white) ![Puppet](https://img.shields.io/badge/Puppet-FFAE1A?style=flat-square&logo=puppet&logoColor=black) ![Bazel](https://img.shields.io/badge/Bazel-43A047?style=flat-square&logo=bazel&logoColor=white) |
| **CI/CD & Progressive Delivery** | ![Buildkite](https://img.shields.io/badge/Buildkite-14CC80?style=flat-square&logo=buildkite&logoColor=black) ![GitLab CI](https://img.shields.io/badge/GitLab_CI-FC6D26?style=flat-square&logo=gitlab&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white) ![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=flat-square&logo=jenkins&logoColor=white) • Azure DevOps • Canary & Blue-Green Deployments |
| **Observability & SRE** | ![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white) ![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white) • M3 • Loki • Tempo • Alertmanager • ![PagerDuty](https://img.shields.io/badge/PagerDuty-06AC38?style=flat-square&logo=pagerduty&logoColor=white) • PromQL • SLI/SLO • DR (RTO/RPO) |
| **Data Center & Networking** | Colocation • Bare-Metal Provisioning • Capacity Planning • NetBox (DCIM) • Rack & Site Topology • VPC/Subnet Design • Multi-NIC Routing • VPN |
| **Security & Compliance** | Zero Trust (Pomerium) • SSH Certificate Authority • PKI/mTLS • ![Vault](https://img.shields.io/badge/HashiCorp_Vault-000000?style=flat-square&logo=vault&logoColor=white) • Keycloak (OIDC/SSO) • IRSA • FedRAMP • PCI DSS • SOC 2 • ISO 27001 |
| **Languages & Operating Systems** | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white) ![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white) • SQL • YAML • ![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black) (Ubuntu, Debian, RHEL) • ![macOS](https://img.shields.io/badge/macOS_Fleet-000000?style=flat-square&logo=apple&logoColor=white) (launchd, MDM) |

---

### 💼 Experience Highlights

#### **Senior Cloud Engineer (L5)** — **Uber Technologies Inc.** *(Jan 2026 – Present | Hyderabad, India)*
- **Fleet Observability at Scale:** Re-architected observability for **1,240+ bare-metal hosts** across 7 labs and 3 data centers, replacing per-host push scripts with pull-based Prometheus federated into M3 through a 4-pod mTLS proxy tier — reaching **100% fleet reporting at >99% scrape success**.
- **Zero-Touch Colo Expansion:** Expanded the physical device-lab estate into **3 new colocation data centers** with per-site Prometheus/Grafana control planes, rack/subnet-aware auto-discovery, Pomerium zero-trust access, and NetBox DCIM.
- **High-Speed Distribution & CLI Tooling:** Built the **DeviceLab CLI (Python)** for discovery of 2,000+ hosts in <3 minutes and parallel execution across 500 nodes in <60s over Pomerium-proxied SSH; designed a 3-tier cascade rsync fabric with multi-NIC routing cutting 10 GB toolchain rollouts across 100 hosts from **2–3 days to <4 hours unattended**.
- **Fleet Reliability & KVM Virtualization:** Operated a **2,000+ Mac mini fleet** backing **6,000+ tethered iOS/Android devices** (migrating 1,008/1,009 nodes with zero CI downtime and cutting unresponsive devices by **60%**); scaled CI capacity onto x86 KVM-backed Android emulator hosts via an idempotent 10-stage bootstrap.

#### **Lead DevOps Engineer** — **Sprinklr** *(Mar 2025 – Dec 2025 | India)*
- Led DevOps across multiple CXM SaaS product lines running **100+ services at 99.99% uptime**.
- Re-architected multi-region **EKS** and **Kafka (KRaft)** clusters on an **ArgoCD GitOps** model with canary and blue-green rollouts, cutting rollback incidents by **70%**.
- Owned SLO-based alerting and on-call across Prometheus, Grafana, Loki, and Tempo, reducing **MTTR by 45%** and **alert noise by 60%**, while delivering **~25% AWS cost reduction** via FinOps dashboards and right-sizing.

#### **Senior DevOps Engineer** — **MavQ Inc. (formerly MTX Group)** *(Jul 2019 – Mar 2025 | Jaipur, India)*
- Architected compliant multi-cloud workloads across **AWS, GCP, and Azure** to **FedRAMP, NIST 800-53, and PCI DSS** controls with zero major audit findings.
- Cut cloud spend **~40% (~$500K annually)** through Terraform-driven autoscaling, spot instance strategy, and continuous right-sizing.
- Re-engineered CI/CD for 40+ microservices (cutting deployment time **40%**), optimized AI/ML serving on **KServe & Knative** (cutting peak response time **30%**), and reduced **RTO by ~50%** with automated cross-region DR drills.

---

### 🏆 Certifications & Recognition

- 🎖️ **Google Cloud Certified — Professional Cloud Architect**
- 🎖️ **Google Cloud Certified — Associate Cloud Engineer**
- 🌟 **Awards:** Employee of the Year (2020) • Above & Beyond Award (2021, 2022) • Employee of the Month (2023)
- 🎓 **Education:** B.Tech in Computer Science Engineering — Amity University, Jaipur (2015 – 2019)
