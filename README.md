# MRx Platform — SharePoint Knowledge Portal

A McKinsey internal knowledge portal for the **Modern Research (MRx) Platform** — a cloud-native, AI-augmented data engineering platform built on Databricks, Azure, and GitHub.

## Site Structure

The portal is organised into four main sections:

| Page | File | Description |
|------|------|-------------|
| 🏠 **Home** | `index.html` | Vision, platform summary, MRx capabilities, and quick links |
| 📊 **Data & AI** | `data-ai.html` | NFR framework, development, data management, testing, error handling, CICD, governance, AI |
| ⚙️ **Infrastructure & DevOps** | `infrastructure-devops.html` | Terraform IaC, CICD pipelines, ops readiness, cost avoidance, observability |
| 🔒 **Security** | `security.html` | Vulnerability management, Wiz Cloud, GitHub Security, monitoring & alerting |

## Key Topics Covered

- **NFR Template/Checks** — tagging, security gates, RTO/RPO, SLAs, HA/DR, LeanIX (BA/AS numbers)
- **Development Framework** — ingestion tools, config/metadata-driven pipelines, AI-assisted development, SonarQube
- **Data Management** — data modelling, catalog structure, medallion layers (Bronze/Silver/Gold), managed tables, partitioning, vacuuming
- **Testing Framework** — data quality framework, unit testing (pytest, chispa)
- **Error Handling** — audit logs, exception log, error reporting and alerting
- **CICD** — Databricks Asset Bundles, GitHub Actions workflows, feature flags, approval gateways
- **Data Governance** — lineage extraction, table/view definitions, data glossary, Alation integration
- **Ops Readiness** — change management, incident management, assignment groups, Jira, ServiceNow, SOX/SOC auditing
- **Infrastructure** — Terraform deployments, compute policies, tagging, cluster resizing, compute optimisation
- **Cost Avoidance** — FinOps cost monitoring, spot instances, auto-termination, right-sizing
- **Platform Observability** — Grafana dashboards, Azure Monitor, SLIs/SLOs
- **Security** — Panorama vulnerability management, Wiz Cloud monitoring, GitHub Advanced Security, incident response
- **AI** — OpenAI, GitHub Copilot/Claude, MCP servers, Databricks AI Assistant, Windsurf (TBD)

## Getting Started

Open `index.html` in a browser to view the portal. All pages are static HTML and CSS — no build step required.
