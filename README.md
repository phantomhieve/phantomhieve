<p align="center">
  <img src="https://raw.githubusercontent.com/phantomhieve/phantomhieve/main/assets/hero.svg" width="100%" alt="Atul Kumar Khetan — Senior Cloud Engineer @ Uber" />
</p>

<p align="center">
  <a href="mailto:khetanatulz@gmail.com"><img src="https://img.shields.io/badge/khetanatulz%40gmail.com-161b22?style=flat-square&logo=gmail&logoColor=EA4335&labelColor=0d1117" alt="Email" /></a>
  &nbsp;
  <a href="https://linkedin.com/in/atul-khetan"><img src="https://img.shields.io/badge/linkedin.com%2Fin%2Fatul--khetan-161b22?style=flat-square&logo=linkedin&logoColor=0A66C2&labelColor=0d1117" alt="LinkedIn" /></a>
  &nbsp;
  <a href="https://phantomhieve.github.io/profile/"><img src="https://img.shields.io/badge/phantomhieve.github.io-161b22?style=flat-square&logo=safari&logoColor=58a6ff&labelColor=0d1117" alt="Portfolio" /></a>
  &nbsp;
  <img src="https://img.shields.io/badge/GCP_Professional_Cloud_Architect-161b22?style=flat-square&logo=googlecloud&logoColor=4285F4&labelColor=0d1117" alt="GCP Architect" />
</p>

I design and operate large-scale infrastructure across public cloud (**AWS, GCP, Azure**) and physical **colocation data centers**. Over the past 7+ years, my focus has been on fleet observability, zero-trust networking, GitOps delivery, and cloud FinOps—scaling systems from bare-metal racks and tethered mobile device fleets to multi-region Kubernetes platforms.

Outside of work, I run a **self-hosted Linux homelab** (`phantomhive` server) wired up with `systemd` daemons, `rsync`/SSH deployment pipelines, Prometheus `node_exporter` textfile collectors, and Grafana alerting to power personal quantitative finance, multi-account brokerage automation, and AI DAG workflows.

---

### 🏛️ Production Track Record

<table>
  <tr>
    <td width="28%" valign="top">
      <b>Uber Technologies</b><br/>
      <sub><b>Senior Cloud Engineer (L5)</b></sub><br/>
      <sub>Jan 2026 – Present · Hyderabad</sub>
    </td>
    <td width="72%" valign="top">
      • <b>Fleet Observability:</b> Re-architected telemetry for <b>1,240+ bare-metal hosts</b> across 7 labs &amp; 3 data centers using pull-based Prometheus federated into M3 over a 4-pod mTLS proxy tier (<b>100% reporting, &gt;99% scrape success</b>).<br/>
      • <b>Zero-Touch Colo Expansion:</b> Onboarded <b>3 colocation data centers</b> with per-site control planes, rack/subnet auto-discovery, Pomerium zero-trust access, and NetBox DCIM.<br/>
      • <b>Fleet &amp; Tooling Scale:</b> Operated a <b>2,000+ Mac mini fleet</b> backing <b>6,000+ tethered iOS/Android devices</b> (cutting unresponsive devices 60%) &amp; KVM-backed x86 Android hosts; built the <b>DeviceLab CLI</b> and a 3-tier multi-NIC rsync fabric cutting 10 GB rollouts across 100 hosts from <b>2–3 days to &lt;4 hours</b>.
    </td>
  </tr>
  <tr>
    <td valign="top">
      <b>Sprinklr</b><br/>
      <sub><b>Lead DevOps Engineer</b></sub><br/>
      <sub>Mar 2025 – Dec 2025 · India</sub>
    </td>
    <td valign="top">
      • Led platform reliability and security standards for <b>100+ CXM SaaS microservices at 99.99% uptime</b>.<br/>
      • Re-architected multi-region <b>EKS</b> &amp; <b>Kafka (KRaft)</b> on an <b>ArgoCD GitOps</b> canary/blue-green model, cutting rollback incidents <b>70%</b>.<br/>
      • Owned SLO alerting across Prometheus, Grafana, Loki &amp; Tempo (<b>-45% MTTR, -60% alert noise</b>) and delivered <b>~25% AWS cost savings</b> via FinOps right-sizing.
    </td>
  </tr>
  <tr>
    <td valign="top">
      <b>MavQ Inc. (MTX Group)</b><br/>
      <sub><b>Senior DevOps Engineer</b></sub><br/>
      <sub>Jul 2019 – Mar 2025 · Jaipur</sub>
    </td>
    <td valign="top">
      • Architected multi-cloud workloads across <b>AWS, GCP, and Azure</b> to <b>FedRAMP, NIST 800-53, and PCI DSS</b> standards with zero major audit findings.<br/>
      • Cut cloud spend <b>~40% (~$500K/yr)</b> via Terraform autoscaling &amp; spot orchestration; optimized AI/ML serving on <b>KServe &amp; Knative</b> (<b>-30% peak latency</b>) and reduced DR <b>RTO by ~50%</b>.
    </td>
  </tr>
</table>

---

### 🖥️ Homelab, Self-Hosting & Financial Engineering

<table>
  <tr>
    <td width="50%" valign="top">
      <b><a href="https://github.com/phantomhieve/finance">Vault — Personal Finance &amp; MCP Hub</a></b><br/>
      <sub><code>Django</code> · <code>ASGI MCP Server</code> · <code>WebAuthn</code> · <code>AI DAG</code></sub><br/><br/>
      Self-hosted wealth &amp; Indian FY tax platform tracking Zerodha equities/MFs, US RSUs, EPF/NPS, real estate, and precious metals. Exposes a native <b>Model Context Protocol (<code>/mcp</code>)</b> server with OAuth 2.0 PKCE and runs a multi-stage AI DAG engine for Sec 112A / 54EC tax harvesting and portfolio stress-testing.
    </td>
    <td width="50%" valign="top">
      <b><a href="https://github.com/phantomhieve/kites-portfolio-automate">Kites Automate — Brokerage Sync Daemon</a></b><br/>
      <sub><code>Python 3.13</code> · <code>Headless Chromium</code> · <code>Prometheus</code></sub><br/><br/>
      Unattended multi-account Zerodha Kite daemon running on my home Ubuntu server. Performs hands-free session renewal via <code>Xvfb</code> + automated TOTP injection, syncs cross-account holdings to Google Sheets with quota-aware state caching, and exports health metrics to Prometheus <code>node_exporter</code>.
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <b><a href="https://github.com/phantomhieve/cashcenter">CashCenter — Wholesale Ledger &amp; AI DAG</a></b><br/>
      <sub><code>Django</code> · <code>PostgreSQL</code> · <code>Gemini DAG</code> · <code>Systemd CI/CD</code></sub><br/><br/>
      Operational double-entry accounting and 5-node AI market intelligence pipeline built for wholesale textile merchants. Generates bilingual (<b>English / हिन्दी</b>) working-capital &amp; turnaround briefs, deployed via automated GitHub Actions over SSH/rsync.
    </td>
    <td width="50%" valign="top">
      <b><a href="https://github.com/phantomhieve/family-tree">Family Tree — Lineage Visualizer</a></b><br/>
      <sub><code>Django</code> · <code>PostgreSQL</code> · <code>Vanilla JS</code></sub><br/><br/>
      Interactive patrilineal family tree web application featuring custom canvas/DOM connector rendering, dark/light theme support, and dynamic relationship modals.
    </td>
  </tr>
</table>

---

### ⚙️ Technical Architecture & Stack

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
    <td>Terraform · Ansible · Puppet · Bazel</td>
  </tr>
  <tr>
    <td><b>Observability &amp; SRE</b></td>
    <td>Prometheus · M3 · Grafana · Loki · Tempo · Alertmanager · PagerDuty · PromQL · node_exporter · SLI/SLO Governance · Disaster Recovery (RTO/RPO)</td>
  </tr>
  <tr>
    <td><b>Security &amp; Compliance</b></td>
    <td>Zero Trust (Pomerium) · SSH Certificate Authority · PKI/mTLS · HashiCorp Vault · Keycloak (OIDC/SSO) · IRSA · FedRAMP · NIST 800-53 · PCI DSS · SOC 2 · ISO 27001</td>
  </tr>
  <tr>
    <td><b>Languages &amp; Education</b></td>
    <td><b>Python · Go · Bash · SQL · YAML</b> &nbsp;|&nbsp; <i>B.Tech CSE, Amity University (2015–2019) · GCP Professional Cloud Architect &amp; Associate Cloud Engineer</i></td>
  </tr>
</table>
