<p align="center">
  <img src="https://raw.githubusercontent.com/phantomhieve/phantomhieve/main/assets/hero.svg" width="100%" alt="Atul Kumar Khetan — Senior Cloud Engineer @ Uber" />
</p>

<p align="center">
  <a href="mailto:khetanatulz@gmail.com"><img src="https://img.shields.io/badge/Email-khetanatulz%40gmail.com-161b22?style=flat-square&logo=gmail&logoColor=EA4335&labelColor=0d1117" alt="Email" /></a>
  &nbsp;
  <a href="https://linkedin.com/in/atul-khetan" target="_blank"><img src="https://img.shields.io/badge/LinkedIn-in%2Fatul--khetan-161b22?style=flat-square&logo=linkedin&logoColor=0A66C2&labelColor=0d1117" alt="LinkedIn" /></a>
  &nbsp;
  <a href="https://phantomhieve.github.io/profile/" target="_blank"><img src="https://img.shields.io/badge/Portfolio-phantomhieve.github.io-161b22?style=flat-square&logo=safari&logoColor=58a6ff&labelColor=0d1117" alt="Portfolio" /></a>
  &nbsp;
  <a href="https://cloud.google.com/certification" target="_blank"><img src="https://img.shields.io/badge/Certified-GCP_Professional_Cloud_Architect-161b22?style=flat-square&logo=googlecloud&logoColor=4285F4&labelColor=0d1117" alt="GCP Architect" /></a>
</p>

I design and operate large-scale infrastructure across public cloud (**AWS, GCP, Azure**) and physical **colocation data centers**. Over the past 7+ years, my focus has been on fleet observability, zero-trust networking, GitOps delivery, and cloud FinOps—scaling systems from bare-metal racks and tethered mobile device fleets to multi-region Kubernetes platforms.

Outside of work, I run a **self-hosted Linux homelab** (`phantomhive` server) wired up with `systemd` daemons, `rsync`/SSH deployment pipelines, Prometheus `node_exporter` textfile collectors, and Grafana alerting to power personal quantitative finance, multi-account brokerage automation, and AI DAG workflows.

---

### Homelab Telemetry & SRE Cockpit

<p align="center">
  <img src="https://raw.githubusercontent.com/phantomhieve/phantomhieve/main/assets/homelab-hud.svg" width="100%" alt="Homelab Telemetry HUD" />
</p>

---

### Production Experience

<table>
  <tr>
    <td width="28%" valign="top">
      <b>Uber Technologies</b><br/>
      <sub><b>Senior Cloud Engineer (L5)</b></sub><br/>
      <sub>Jan 2026 – Present · Hyderabad</sub>
    </td>
    <td width="72%" valign="top">
      • <b>Colocation &amp; Bare-Metal Architecture:</b> Architected infrastructure and telemetry across <b>3 colocation data centers and 1,240+ bare-metal hosts</b>, delivering zero-touch site onboarding, rack discovery, and high-fidelity federated observability (&gt;99% scrape reliability).<br/>
      • <b>Fleet Scale &amp; Automation:</b> Scaled platforms supporting a <b>2,000+ host fleet and 6,000+ mobile devices</b>; engineered high-throughput deployment fabrics that cut fleet-wide rollout times from <b>days to &lt;4 hours</b>.
    </td>
  </tr>
  <tr>
    <td valign="top">
      <b>Sprinklr</b><br/>
      <sub><b>Lead DevOps Engineer</b></sub><br/>
      <sub>Mar 2025 – Dec 2025 · India</sub>
    </td>
    <td valign="top">
      • <b>Platform Reliability &amp; GitOps:</b> Owned availability and reliability standards for <b>100+ CXM SaaS microservices at 99.99% uptime</b>; led the migration of multi-region Kubernetes and Kafka architectures to a GitOps model, reducing rollback incidents by <b>70%</b>.<br/>
      • <b>Observability &amp; FinOps:</b> Standardized enterprise SLI/SLO monitoring (cutting MTTR by <b>45%</b> and alert noise by <b>60%</b>) while delivering <b>~25% cloud infrastructure cost savings</b> through workload right-sizing.
    </td>
  </tr>
  <tr>
    <td valign="top">
      <b>MavQ Inc. (MTX Group)</b><br/>
      <sub><b>Senior DevOps Engineer</b></sub><br/>
      <sub>Jul 2019 – Mar 2025 · Jaipur</sub>
    </td>
    <td valign="top">
      • <b>Multi-Cloud Governance &amp; Security:</b> Architected enterprise platforms across <b>AWS, GCP, and Azure</b> compliant with <b>FedRAMP, NIST 800-53, and PCI DSS</b> standards with zero major audit findings.<br/>
      • <b>FinOps &amp; Serving Optimization:</b> Reduced cloud infrastructure spend by <b>~40% (~$500K/yr)</b> via automated elasticity, and optimized AI/ML serving performance to cut peak latency by <b>30%</b>.
    </td>
  </tr>
</table>

---

### Homelab, Self-Hosting & Financial Engineering

<table>
  <tr>
    <td width="50%" valign="top">
      <b><a href="https://github.com/phantomhieve/finance">Vault — Personal Finance &amp; MCP Hub</a></b><br/>
      <sub><code>Django</code> · <code>ASGI MCP Server</code> · <code>WebAuthn</code> · <code>AI DAG</code></sub><br/><br/>
      Self-hosted wealth and portfolio intelligence platform tracking multi-asset holdings (equities, mutual funds, US RSUs, and real estate). Exposes a native <b>Model Context Protocol (<code>/mcp</code>)</b> server with OAuth 2.0 PKCE and an AI DAG engine for portfolio analytics and stress-testing.
    </td>
    <td width="50%" valign="top">
      <b><a href="https://github.com/phantomhieve/kites-portfolio-automate">Kites Automate — Brokerage Sync Daemon</a></b><br/>
      <sub><code>Python 3.13</code> · <code>Headless Chromium</code> · <code>Prometheus</code></sub><br/><br/>
      Unattended multi-account Zerodha Kite automation daemon operating on a self-hosted Linux server. Automates headless session renewals via TOTP injection, syncs cross-account holdings to Google Sheets, and exports telemetry to Prometheus.
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <b><a href="https://github.com/phantomhieve/cashcenter">CashCenter — Wholesale Ledger &amp; AI DAG</a></b><br/>
      <sub><code>Django</code> · <code>PostgreSQL</code> · <code>Gemini DAG</code> · <code>Systemd CI/CD</code></sub><br/><br/>
      Operational double-entry accounting platform and 5-node AI market intelligence pipeline built for wholesale merchants. Generates automated bilingual (<b>English / हिन्दी</b>) working-capital and turnaround briefs, deployed via automated CI/CD over SSH.
    </td>
    <td width="50%" valign="top">
      <b><a href="https://github.com/phantomhieve/family-tree">Family Tree — Lineage Visualizer</a></b><br/>
      <sub><code>Django</code> · <code>PostgreSQL</code> · <code>Vanilla JS</code></sub><br/><br/>
      Interactive patrilineal lineage visualization web application featuring custom canvas/DOM connector rendering, dark/light theme support, and dynamic relationship modals.
    </td>
  </tr>
</table>

---

### Technical Architecture & Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=aws,gcp,kubernetes,docker,terraform,ansible,prometheus,grafana,python,go,bash,linux,postgres,git&theme=dark" alt="Technical Arsenal" />
</p>

<table>
  <tr>
    <td width="28%"><b>Cloud &amp; Bare-Metal</b></td>
    <td width="72%">AWS (EKS, EC2, S3, IAM, VPC, Direct Connect, Secrets Manager) · GCP (GKE, Cloud SQL, Memorystore, Cloud Armor, GCS) · Azure · Colocation DCIM (NetBox) · KVM · macOS &amp; Linux Fleet at Scale</td>
  </tr>
  <tr>
    <td><b>Orchestration &amp; Delivery</b></td>
    <td>Kubernetes · Docker · Helm · ArgoCD (GitOps, Canary &amp; Blue-Green) · Apache Kafka (KRaft) · KServe · Knative · Buildkite · GitHub Actions · GitLab CI · Jenkins</td>
  </tr>
  <tr>
    <td><b>Infrastructure as Code</b></td>
    <td>Terraform · Ansible · Puppet · Bazel · Linux Shell Scripting</td>
  </tr>
  <tr>
    <td><b>Observability &amp; SRE</b></td>
    <td>Prometheus · M3 · Grafana · Loki · Tempo · Alertmanager · PagerDuty · PromQL · node_exporter · SLI/SLO Governance · Disaster Recovery (RTO/RPO)</td>
  </tr>
  <tr>
    <td><b>Security &amp; Compliance</b></td>
    <td>Zero Trust (Cloudflare Zero Trust) · SSH Certificate Authority · PKI/mTLS · HashiCorp Vault · Keycloak (OIDC/SSO) · IRSA · FedRAMP · NIST 800-53 · PCI DSS · SOC 2 · ISO 27001</td>
  </tr>
  <tr>
    <td><b>Languages &amp; Systems</b></td>
    <td><b>Python 3.13 · Go · Bash · SQL · Django ASGI · FastAPI · YAML</b></td>
  </tr>
  <tr>
    <td><b>Education &amp; Credentials</b></td>
    <td><b>B.Tech in Computer Science &amp; Engineering</b>, Amity University (2015–2019)<br/><b>Google Cloud Certified:</b> Professional Cloud Architect · Associate Cloud Engineer</td>
  </tr>
</table>

---

<p align="center">
  <sub><b>Crafted with Infrastructure as Code · Powered by Linux.</b></sub>
</p>
